# wgdda
Which God-Damn Dialog Alias is a shell script you can source into your 
environment to alias dialog to something you are sure you have. It's easy to
use. Just include it in your shell script this way.

        . wgdda

and **dialog** will be an alias for whichever alias for dialog your distro
installs. Usually it will be gdialog, kdialog, whiptail or zenity.

You can customize it's behavior by specifying

        NOGUI_DIALOG="true"

in your shell script to force it to simply choose between terminal mode versions
of the script. If you want to always set NOGUI_DIALOG="true" just include it in
~/.profile
