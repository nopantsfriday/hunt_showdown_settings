[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/nopantsfriday/restart_steam_client/blob/master/LICENSE)
<br>Feel free to use, copy, fork, modify, merge, publish or distribute the article and/or parts of the article.

# My personal Hunt: Showdown optimization attempts
These are my personal Hunt: Showdown Windows 10/11 optimization attempts to improve frames per second, reduce frames drops and stutter. Keep in mind that not every setting may be right for you.

## Hunt in-game settings

### Basic Settings
- Render Resolution Scale ```100```
- Video Memory (VRAM) Usage Target ```90%```
- Object Quality ```low```
- Texture Quality ```low```
- Texture Filtering ```16x (Anisotropic)```
- Anti Aliasing SMAA ```1x```
- Lighting Quality ```low```
- Shadow Quality ```low```
- Effect Quality ```low```
- Post-Process Quality ```low``` (not off)
- V-Sync ```off```
- Max FPS ```180```
- Depth of Field ```off```
- Motion Blur ```off```
### Advanced Settings
- Surface Format Optimization ```off```
- Toggle GPU Tesselation ```off```
- Use 2 Pass Scene Rendering ```off```
- Use 2 Pass Lighting ```off```

## Nvidia 3D Settings
- Image Scaling ```Off```
- Image Sharpening ```Off```
- Anisotropic Filtering	```Off```
- Antialiasing - FXAA ```Off```
- Antialiasing - Gamma Correction ```Off```
- Antialiasing - Mode ```Override any application setting```
- Antialiasing - Transparancy ```Off```
- Background Application Max Frame Rate ```Off```
- CUDA – GPUS ```All```
- Low Latency Mode	```Ultra```
- Max Frame Rate ```Off``` or ```Desired value```
- Monitor Technology ```G-SYNC Compatible```
- Multi-Frame Samples AA (MFAA) ```Off```
- OpenGL GDI Compatibility ```Prefer performance```
- OpenGL Rendering GPU ```Select GPU here```
- Power Management Mode	```Prefer Max Performance```
- Preferred refresh rate ```Highest available```
- Texture filtering - Anisotropic sample optimization ```Off```
- Texture filtering - Negative LOD bias ```Allow```
- Texture filtering - Quality ```High performance```
- Texture filtering - Trilinear optimization ```On```
- Threaded optimization ```On```
- Tripple buffering ```Off```
- Vertical Sync	```Use the 3D application setting```
- Virtual Reality pre-rendered frames ```1```

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
