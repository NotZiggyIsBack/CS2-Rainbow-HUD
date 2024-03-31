# CS2-Rainbow-HUD
Makes your cs HUD rainbow 🌈

## How to download/make
### Download .cfg file
You can download `rainbow.cfg` file from this repo and put it here:  <br>
`C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

### Manually create .cfg file
If you don't want to download the file in this repo for some reason here is how to do it manually. <br>
1. Navigate to this folder: `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
2. Create a new text file
3. Paste the following content into the file
```
alias colors "colors0"
alias colors0 "cl_hud_color 0; alias colors colors1"
alias colors1 "cl_hud_color 1; alias colors colors2"
alias colors2 "cl_hud_color 2; alias colors colors3"
alias colors3 "cl_hud_color 3; alias colors colors4"
alias colors4 "cl_hud_color 4; alias colors colors5"
alias colors5 "cl_hud_color 5; alias colors colors6"
alias colors6 "cl_hud_color 6; alias colors colors7"
alias colors7 "cl_hud_color 7; alias colors colors8"
alias colors8 "cl_hud_color 8; alias colors colors9"
alias colors9 "cl_hud_color 9; alias colors colors10"
alias colors10 "cl_hud_color 10; alias colors colors11"
alias colors11 "cl_hud_color 11; alias colors colors12"
alias colors12 "cl_hud_color 12; alias colors colors13"
alias colors13 "cl_hud_color 13; alias colors colors0"
bind d "+right; colors;"
bind a "+left; colors;"
bind w "+forward; colors;"
bind s "+back; colors;"
```
4. Save the file with any name you want **but it must end in .cfg!**

## How to use
When you load the game open in-game console with <kbd>~</kbd> key (*Before <kbd>1</kbd> on your keyboard*) and type following command: <br>
`exec {file name here}.cfg` *without {} ofc 😊*

*Optional:* in startup options you can add same command `-exec {file name here}.cfg` to auto execute when you start cs2. This is needed if you always want rainbow HUD since after you exit the game it will save last HUD color and won't change it until you manually change the color in settings or run the command again.

💜 **@NotZiggyIsBack**
