# Hungarian QWERTY layout
This is an altered hungarian keyboard layout for Windows.

## List of modifications
- The `Y` and `Z` keys are switched
- Default hungarian numpad decimal separator (`,`) is replaced with `.`
- Eliminated "dead-keys": using `AltGr` modifier will insert the character immediately, there is no need for additional key press
- `AltGr`+`Shift` modifier will invert some keys:
  - `ä` will be `Ä`
  - `Ä` will be `ä`
  - `đ` will be `Đ`
  - `Đ` will be `đ`
  - `ł` will be `Ł`
  - `Ł` will be `ł`
  - `í` will be `Í`
  - `Í` will be `í`

## Install
1. Get the [zip version](https://github.com/pcdevil/huqwerty/archive/master.zip) of the repository
2. Unzip it, and then run `build/setup.exe`

### Uninstall
The standard method works well: Open _Programs and Features_ (via the _Control Panel_ or directly from the _Start menu_), and search the tool as _Hungarian QWERTY layout_.

## Editing
After forking, the `src/huqwerty.klc` file can be opened with [Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/goglobal/bb964665.aspx).
