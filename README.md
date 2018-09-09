# Blacked/Blacked Raw metadata agent

This metadata agent will receive data from [Blacked](https://blacked.com) & [Blacked Raw](https://blackedraw.com) for full length movie releases.

Features
============
The agent searches in two ways, Scene title or scene date with atleast one star name
Currently the features of this metadata agent are:
- Grabs Metadata
- Title
- Studio
- Release Data
- Porn Stars stored in Actors with photo
- Movie Poster
- Video banner as video background


File Naming
============
** Plex Video Files Scanner needs to be set as the library scanner for best results. **
For best results, file names should follow the layout below
Site - Scene Title.[ext]
Site - YYYY-MM-DD - Porn Star Names.[ext]
Site - YYYY-MM-DD - Porn Star Name Porn Star Name.[ext]

Examples:
Blacked.com - Hot Vacation Adventures.mp4
Blacked.com - 2018-09-07 - Alecia Fox.mp4
Blacked.com - 2018-09-07 - Alecia Fox Joss Lescaf.mp4
Blackedraw.com - Pass Me Around.mp4
Blacked.com - 2018-09-04 - Haley Reed.mp4
Blacked.com - 2018-09-04 - Haley Reed Jason Luv.mp4

The site can be missing from the filename, but both sites will then be searched possibly causing a mismatch.

Installation
============
Here is how to find the plug-in folder location:
https://support.plex.tv/hc/en-us/articles/201106098-How-do-I-find-the-Plug-Ins-folder-

Plex main folder location:

    * '%LOCALAPPDATA%\Plex Media Server\'                                        # Windows Vista/7/8
    * '%USERPROFILE%\Local Settings\Application Data\Plex Media Server\'         # Windows XP, 2003, Home Server
    * '$HOME/Library/Application Support/Plex Media Server/'                     # Mac OS
    * '$PLEX_HOME/Library/Application Support/Plex Media Server/',               # Linux
    * '/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/', # Debian,Fedora,CentOS,Ubuntu
    * '/usr/local/plexdata/Plex Media Server/',                                  # FreeBSD
    * '/usr/pbi/plexmediaserver-amd64/plexdata/Plex Media Server/',              # FreeNAS
    * '${JAIL_ROOT}/var/db/plexdata/Plex Media Server/',                         # FreeNAS
    * '/c/.plex/Library/Application Support/Plex Media Server/',                 # ReadyNAS
    * '/share/MD0_DATA/.qpkg/PlexMediaServer/Library/Plex Media Server/',        # QNAP
    * '/volume1/Plex/Library/Application Support/Plex Media Server/',            # Synology, Asustor
    * '/raid0/data/module/Plex/sys/Plex Media Server/',                          # Thecus
    * '/raid0/data/PLEX_CONFIG/Plex Media Server/'                               # Thecus Plex community    

Get the latest source zip in github release at https://github.com/PhoenixPlexCode/Blacked.bundle > "Clone or download > Download Zip
- Open Blacked.bundle-master.zip and copy the folder inside (Blacked.bundle-master) to the plug-ins folders
- Rename folder to "Blacked.bundle" (remove -master)

Notice
============
No real error checking is implemented. It was quickly tested on ~30 titles before the initial release.

** Plex Video Files Scanner needs to be set as the library scanner for best results. **