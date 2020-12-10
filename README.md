# BigBox_PS4_home_button_Launcher
Autohotkey script for openeing LaunchBox's BigBox via bluetooth playstation 4 controllers home button.

I found the autohotkeyscript online and edited such that it works for my PS4 controller that is connected to my PC via bluetooth. Was very useful for my setup and may help others also.

## Instructions
Step 1) Install [autohotkey](https://www.autohotkey.com/) on to your windows machine.

Step 2) edit `line 59` in the script for your location of `BigBox.exe`.

Step 3) put the 'launchbox_autohotkeyscript.ahk' script into `"C:\Users\USERNAME\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\"`

Step 4) thats it, it should all be working! try opening big box via your home button


## Trouble Shooting
This only works for windows machine, If the script runs okay but does not react to your home button, when in bigbox you can set the key mappings of your controller which will reveal the button identfication numbers for your controller. On mine `Button 13` was the `ps4 logo home button` on my controller, this may differ for your controller.

Not sure on who the author of autohotkeyscript I found, but I am very gratefull and wish I could credit them, their raw code can be found at [pastebin.com](https://pastebin.com/Ua33mAj8) as a follow from a [reddit thread](https://www.reddit.com/r/launchbox/comments/6rwxm4/launch_bigbox_with_xbox_home_button_builtin/).