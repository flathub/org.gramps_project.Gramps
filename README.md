# org.gramps_project.Gramps 
The Gramps Project strives to produce a genealogy program that is both intuitive for hobbyists and feature-complete for professional genealogists.  The website for Gramps is at https://gramps-project.org/

To request another prerequisite be added to support another Gramps add-on, you can request it at the gramps project flatpak github or at the flathub Gramps flatpak github.

https://github.com/gramps-project/flatpak

https://github.com/flathub/org.gramps_project.Gramps

***Please Note***
For security reasons, the flatpak for Gramps 5.2 will lose access to the entire home directory in exchange for xdg access to only Documents, Downloads, and Pictures. If your media directory for Gramps is not in Documents, Downloads, or Pictures, then you can either:
1. Move your media directory to either Documents, Downloads, or Pictures, and then use the Media Tool in Gramps to change the path so that Gramps can see the media again
2. Use flatseal (a flatpak permissions app available at flathub) to allow Gramps access to whereever your media directory is located.
3. If the 5.2 version of Gramps does not show your tree, then close Gramps, open your file browser to the directory that the .gramps file (or .gpkg file if a backup), right click on the file, and select "Open with Gramps". It will take a couple minutes to convert to the 5.2 version, but it should work as long as you make sure the file and all related pictures are in Documents, Pictures, or Downloads.

Also, the old version of Berkeley Database (BSDDB) that was included with the Gramps 5.0 and 5.1 flatpaks will be dropped for 5.2.

Please make regular full backups of your important genealogy files, and include any attached media files for your genealogy in your backups for your convenience.
