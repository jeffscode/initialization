# initialization-script

The initialisation script was originally written by Carl Duff for the Evo/Lution installer, to allow the user to select the latest
stable or testing version of lution-ais, download it, extract it and start Lution-ais. The initialisation scripts main purpose is it eliminates the need to download an entire iso every time the installer is updated. 

Lution-ais is Carl's Arch install script that is made specifically for Evo/Lution, which uses the Openbox window manager. 

For CLI/Lution to be able to cleanly use Lution-ais, which had features that require xorg, etc, it requires some minor 
modifications.

The modified and renamed, initialization script does everything the original script did plus it edits Lution-ais 
to trade the gparted tool for fdisk. It also changes the dialog to properly reflect the changes in all the supported
languages. 

This allows for the development and maintenance of one version of Lution-ais rather than two slightly different versions.

