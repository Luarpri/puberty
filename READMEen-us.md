# Puberty
A Scratch Jr runtime running in Scratch. This is just a proof of concept.
![An image running an empty project](screenshot.png)
## Unimplemented Blocks
- Loops, wait blocks, and really any block that runs across multiple frames
  - Only the "forever" loop is supported
- User sounds
- Pages (works but not very well)
### Implemented Blocks
- Move right/left [x]
- Play pop
- Up [x]
- Down [x]
- Turn right/left [x]
- Go to beginning
- Say [x]
- Grow/shrink [x]
- Show/hide
- Reset size
# Considerations

Because it's very early, there are a few things to keep in mind:
- Scripts will only run if they are in "Ta" (temporary measure)
- There may be many bugs (report them in issues if you find them)
- If you have a custom sprite, all objects They will have that sprite, even if they don't have said sprite.
- Official Scratch Jr sprites will not load.
## Debugging
There are some debug keys<br>

`1` Shows runtime variables<br>
`2` Hides variables<br>
`3` Saves the runtime log to `log.txt`
# Credits
- [Scratch Everywhere!](https://github.com/ScratchEverywhere/ScratchEverywhere) for inspiring this project<br>
- The MIT team for making Scratch Jr<br>
- Mistium for making [MistWarp](https://warp.mistium.com/)
- TurboWarp extensions for carrying this thing
