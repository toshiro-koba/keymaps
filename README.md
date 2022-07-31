# keymaps

~/projects/keymap/qmk_firmwareにて、make ergodash/rev1:kobatch:avrdudeを実行
キーマップをいじる場合は、
`qmk_firmware/keyboards/ergodash/rev1/keymaps/(Name)` 内の　`keymap.c` を変更し、
`qmk_firmware/` にて `make ergodash/rev1:(Name)` を実行しコンパイルする。

その後 `make ergodash/rev1:default:avrdude` を実行しマイコンに書き込む。

FYI:
- [qmk\_firmware/keycodes\.md at master · qmk/qmk\_firmware](https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md)
