# Day-1, Study basic knowledge, 2023-09-17

1. The screen resolution is 400 × 240 pixels, at 173 pixels per inch
2. By default, Playdate games run at 30 frames per second (fps). The maximum refresh rate you can set is 50 fps. We need to use C rather then Lua for 50 fps because of performance.
3. Playdate’s 1-bit screen might suggest the audio of an older console, limited to beeps and boops, but it actually has very modern sound capabilities. You can play compressed or uncompressed audio at 44,100 Hz.
4. There are d-pad, A & B button, crank and Accelerometer. Crank is the most special thing in playdate.
5. I use windows for developer. This video can help you setup the environment. https://www.youtube.com/watch?v=ZPcfC98JogQ
6. Lua is an interest program language very simple. When we finish easy code like below, the code run
```
import "CoreLibs/graphics"
import "CoreLibs/object"

local gfx <const> = playdate.graphics


function playdate.update()
	gfx.drawCircleAtPoint(100, 100, 100)
end

```
8. After setup PlayDate-SDK, we can use pdc "source code folder" "output folder" to build the application and use simulator to run and play it
