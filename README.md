# cocot46plus

![cocot46plus_header00](https://user-images.githubusercontent.com/88039287/167350336-b81adab9-fa34-40c3-8fe5-a35bc3eb2048.jpg)

cocot46plus is a column staggered keyboard with 46 keys, a 34mm-trackball and a rotary encoder.

- Keyboard Maintainer: [aki27kbd](https://github.com/aki27kbd) [@aki27kbd](https://twitter.com/aki27kbd)
- Hardware Supported: cocot46plus PCB, ProMicro
- Hardware Availability: [BOOTH](https://aki27.booth.pm/)

[Firmware](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/cocot46plus)

[Build Guide](To be updated...)

### Special keycodes

Value    | Keycode   |Description
---------|-----------|-----------
`0x5DA7` | `CPI_SW`  |Switch CPI
`0x5DA8` | `SCRL_SW` |Switch scroll divider
`0x5DA9` | `ROT_R15` |Rotate sensor coordinate by 15 degrees clockwise
`0x5DAA` | `ROT_L15` |Rotate sensor coordinate by 15 degrees counterclockwise
`0x5DAB` | `SCRL_MO` |Enable scroll mode when pushed
`0x5DAC` | `SCRL_TO` |Toggle scroll mode. Once pushed, mouse mode and scroll mode are switched.
`0x5DAD` | `SCRL_IN` |Invert scroll direction
