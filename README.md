#PCB based MIDI Tesla Coil

Docs todo

Flash with dfu-util -d 0483:df11 -a 0 -s 0x8000000:leave -D build/pcbtcMIDI.bin

Midi stack based on:
https://github.com/keshikan/CureMIDI 

## USB-MIDI Interface (2IN/2OUT) for STM32 "CureMIDI"

### Author

(c) 2018 Keshikan ( [Website](http://www.keshikan.net/),  [Twitter](https://twitter.com/keshinomi_88pro) )

### License

* USB MIDI Class Driver: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
* STM32 CubeF0: BSD-3-Clause based.
* Other Codes, Hardware, Schematic: [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)

See also [LICENSE.md](./LICENSE.md)
