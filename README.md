APBr-Shader-Crosshair
=====================

Customizable crosshair for the game APB Reloaded

Installation:
Copy all the Crosshair*.usf files to Engine\Shaders (Crosshair.usf, CrosshairSettings.usf, CrosshairDot1.usf, CrosshairDot2.usf, ...)
Add '#include "Crosshair.usf"' to APBUberPostProcessBlendPixelShader.usf before the bottom closing "}". or use the included one.
Edit CrosshairSettings.usf and enable the crosshair and change settings.



Notes:
SCREEN_SIZE_X SCREEN_SIZE_Y must match your monitor resolution.
Won't work if bloom is off
Included APBUberPostProcessBlendPixelShader.usf is from rtw
Its work in progress
Make Sure your resolution is correct in APBr.. going from windowed to full screen sets 1080 to 1050 or something weird.
Feel free to bundle it with your own shader pack. just leave the notes area alone 