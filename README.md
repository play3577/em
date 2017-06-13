
# Em

Em is a GameBoy emulator written in Unity/C# for iPhone/iPad/Android. Other platforms probably work fine as well.
Only GameBoy ROMs are supported, GameBoy Color ROMs are work in progress.

## Requirements

Unity 5.6+ is required to execute and generate builds of the emulator.

## Tests

CPU instruction set accuracy test results (Blargg's cpu_instrs.gb test ROM):

[![Tests](https://s23.postimg.org/uox8s2et7/Screen_Shot_2017-06-12_at_11.21.37_PM.png)](https://postimg.org/image/nygrimrnb/)

## Credits

Memory Management partially ported from GameBoyCore.
Partially ported video, HDMA, and double speed mode procedure from the STOP opcode from MeBoy 2.2