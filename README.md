# doom3-linux-widescreen-fix
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.

# Create a an autoexec.cfg and drop it into your base doom3 directory in Steam client.Recommended Proton versions 5.13 and 6.8 (they don't give black textures as experimental does)
# Explanation
# Your monitor resolution:
* seta r_customHeight "1080"
* seta r_customWidth "1920"
# Fullscreen On:
* seta r_fullscreen "1"
# FOV
* seta r_mode "-1"
# Aspect Ratio for 4:3 it will be 0,for 16:9 it will be 1,for 16:10 it will be 2
* seta r_aspectratio "1"
# Your display refresh v-sync rate current 60,you can set according to your monitor refresh rate 144.160,180,244,etc,just make sure you enabled it in display configuration.
* seta r_displayRefresh "60"
# Antialiasing from 0 to 4 to 8,depends on how you like it
* seta r_multisamples "0"
* vid_restart

# My YT channel:
https://www.youtube.com/c/SilentGamePLS/
# Enjoy  silentgamepls!
