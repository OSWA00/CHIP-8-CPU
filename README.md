# CHIP-8-CPU #

## Opcode ##

| Operation | Byte 1 | Byte 2 | Byte 3 | Byte 4 |
| :---:     | :---:  | :---:  | :---:  | :---:  |
| ADD       | 0x8    | Reg(x) | Reg(y) | 0x4    |
| CALL      | 0x2    | n      | n      | n      |
| RETURN    | 0x0    | 0x0    | 0xE    | 0xE    |
