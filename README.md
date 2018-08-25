# retrosmc-wiimote
Automated Wimote for retrosmc

## How to:
1. Follow this official Wiimote tutorial for RetroPie. (Method 2) https://github.com/RetroPie/RetroPie-Setup/wiki/Wiimote-Controller#method-2-moltengamepad

2. When you got your wiimote working on gamepad detection screen, connect osmc with FTP.

3. After that copy my retropie.sh script into the /home/USERNAME/RetroPie/scripts/retropie.sh file. Change [ADDRESS] to your Wiimote address(es). Then Save the file.

4. Reboot your osmc. Before starting retrosmc from programs in osmc, press 1+2 on your Wiimote(s). When leds started blinking, launch retrosmc. Now it should be connected to your Retropie. Have fun!

`NOTE:` For this tutorial to work, you must complete method 2 successfully.
`NOTE2:` You can add many Wiimotes as you want. Just copy and paste "pair and connect" lines after them. You have to change adress though.

If it is not working, feel free to open an issue! :)
