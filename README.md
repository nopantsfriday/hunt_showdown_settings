[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/nopantsfriday/restart_steam_client/blob/master/LICENSE)
<br>Feel free to use, copy, fork, modify, merge, publish or distribute the script and/or parts of the script.

# My personal Hunt: Showdown optimization attempts
These are my personal Hunt: Showdown Windows 10/11 optimization attempts to improve frames per second, reduce frames drops and stutter. Keep in mind that not every setting may be right for you.

## Hunt in-game settings
![1.png](https://raw.githubusercontent.com/nopantsfriday/hunt_showdown_settings/main/1.png)
![2.png](https://raw.githubusercontent.com/nopantsfriday/hunt_showdown_settings/main/2.png)
![3.png](https://raw.githubusercontent.com/nopantsfriday/hunt_showdown_settings/main/3.png)

## Nvidia 3D Settings
![nvidia.png](https://raw.githubusercontent.com/nopantsfriday/hunt_showdown_settings/main/nvidia.png)

# Application settings
## Disable hardware acceleration in Discord
- Open ```Discord```
- Open ```Settings```
- Go to ```Advanced```
- ```Hardware Acceleration``` -> **off**

## Close Google Chrome while playing 
Seriously, close it. It also uses hardware acceleration and could use up precious ressources of your GPU.

## Disable Nvidia overlay or uninstall GeForce Experience
- Open ```GeForce Experience```
- Go to ```Settings```
- ```In-Game Overlay``` -> **off**

## Disable Steam overlay
> This will disable the option to invite friends in-game but could help out if you are experiencing stutter issues
- Open ```Steam```
- Open ```Settings```
- Go to ```In-Game``` 
- ```Enable the Steam overlay while in-game``` -> **off** <br />

# Windows settings
## Windows performance Settings
- Use the ```Windows key + R``` keyboard shortcut to open the Run command.
- Type ```sysdm.cpl``` and click OK
- Under ```Performance``` click the Settings button
- Set to ``` Adjust for best performance ```
- Set ```Smooth edges of screen fonts``` to **on**

## Enable Windows 10 Ultimate Performance Power Plan
- To activate the power plan open powershell and enter
```powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61```
- Use the ```Windows key + R``` keyboard shortcut to open the Run command
- Type ```powercfg.cpl```
- Choose the ```Ultimate Performance Power Plan```

## Enable Windows 10 Hardware-accelerated GPU scheduling
- Press ```Windows key + I```
- Go to ```System```
- Select ```Display``` in the left menu pane
- On the bottom of the right pane click ```Graphics settings```
- Turn **on** the toggle for ```Hardware-accelerated GPU scheduling```
- (Optional) If your monitor supports it, set ```Variable refresh rate``` to **on**
- Restart your computer

## Enable Windows 10 game mode
- Press ```Windows key + I```
- Type ```game mode```
- Click ```Game Mode settings``` (or ```Turn on Game Mode```)
- On the Gaming screen, click ```Game Mode```
- Set Game Mode to ```on```

# BIOS settings
## Enable  Resizable BAR in BIOS
- The options to actiavte this depends on your motherboard manufacturer.
