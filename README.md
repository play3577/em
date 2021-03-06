
# Em

![GB1](https://thumbs.gfycat.com/PlainWellwornAffenpinscher-size_restricted.gif)
![GB2](https://thumbs.gfycat.com/WeirdHighKitty-size_restricted.gif)

Em is a GameBoy emulator written in Unity/C# for iPhone/iPad/Android. Other platforms should work fine as well.
Only GameBoy ROMs are supported, GameBoy Color ROMs are work in progress.

## Requirements

Unity 5.6+ is required to execute and generate builds of the emulator. iOS builds were using XCode 8.3.

## Documentation

You can find information about the many details and internals of Game Boy Development [here](https://github.com/avivace/awesome-gbdev).

## Tests

CPU instruction set accuracy test results ([Blargg's cpu_instrs.gb](http://gbdev.gg8.se/files/roms/blargg-gb-tests/) test ROM):

<img src="https://s23.postimg.org/uox8s2et7/Screen_Shot_2017-06-12_at_11.21.37_PM.png" width="200">

## TODO

- [x] Support Game Boy Classic ROMs
- [x] Keyboard/Mobile Controls
- [x] Support Game Boy Color ROMs
- [x] MBCRAM/SRAM memory is persisted between sessions
- [ ] Improve UI
- [ ] Sound
- [ ] Save/Restore state

## Known Issues

GBC emulation have some minor graphic glitches

## Credits

Memory Management partially ported from GameBoyCore.
Partially ported video, HDMA, and double speed mode procedure from the STOP opcode from MeBoy 2.2

## License

Em is open-source software released under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
