# SuperMarioWorld:
Inspired by Seth Bling's MarI/O

# Description:
- Update to [Seth Bling's Mar I/O](https://www.youtube.com/watch?v=qv6UVOQ0F44) lua code
- Link to original [NEAT paper](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) by Ken. Stanley & Risto Miikkulainen
- Moved GUI overlay to form window, but kept a version with the GUI overlay
- Added "Start" & "Stop" buttons
- These changes will increase the training period considerably; ~100 generations to consistently beat the level
- Updated fitness function to take into account: coins, score, and damage
- Distance are now weighted

# Instructions:
1. Install [BizHawk](http://tasvideos.org/BizHawk.html)
2. Get the rom of Super Mario World (USA)
3. Clone this repository or download the zip file
4. Move the neat-mario folder in your \BizHawk-2.2\Lua\SNES\ folder. (like: BizHawk-2.2\Lua\SNES\neat-mario)
5. Open config.lua and change variable _M.BizhawkDir to point on your BizHawk directory
6. Open BizHawk
7. Open Super Mario World (USA) rom file
8. Once opened, go to Tools -> Lua Console
9. Select "mario-neat.lua" or "mario-neat (GUI overlay).lua" from step 4
10. The NEAT control window will display and you can then click Start to begin training
