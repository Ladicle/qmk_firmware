# The custom keymap for Mint60

## Preparation

```
$ ./utils/text-decoration.sh
$ sudo apt-get install binutils-avr gcc-avr avr-libc avrdude
```

## Installation

1. Go to this repository root
2. Run `make mint60:custom` 
3. Connect micro-USB to the left keyboard
4. Run `sudo make mint60:custom:avrdude`
5. Push the sync button on the back of the keyboard
6. Repeat the same steps from 3 to 5 for the right keyboard 
