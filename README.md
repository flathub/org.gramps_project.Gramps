# org.gramps_project.Gramps 
The Gramps Project strives to produce a genealogy program that is both intuitive for hobbyists and feature-complete for professional genealogists.  The website for Gramps is at https://gramps-project.org/

To request another prerequisite be added to support another Gramps add-on, you can request it at the gramps project flatpak github or at the flathub Gramps flatpak github.

https://github.com/gramps-project/flatpak

https://github.com/flathub/org.gramps_project.Gramps

***Please Note***
For now, both attempts to use specific xdg directories have caused problems for users of the Gramps flatpak.
At this time, flathub rules blocking data directory access prevents users from choosing to go between a flatpak
installation and a system installation, which causes data loss for some users. Even using persist like flathub says
instead of filesystem can cause data loss for users moving from the flatpak to a system install. The required directories for databases started 
with Gramps 5.1 and earlier is ~/.gramps, while the required directories for databases started with a system installation 
of Gramps 5.2 are xdg-data, xdg-config, xdg-cache. Once flathub stops blocking these directories, we can remove home
directory access and go back to xdg access.

Also, the old version of Berkeley Database (BSDDB) that was included with the Gramps 5.0 and 5.1 flatpaks will be dropped for 5.2.

Please make regular full backups of your important genealogy files, and include any attached media files for your genealogy in your backups for your convenience.
