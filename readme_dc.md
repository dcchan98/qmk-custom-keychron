# Changing keymap for q1 he

- Change file in `keyboards\keychron\q1_he\ansi_encoder\keymaps\default\keymap.c`
- Compile changes
  - Open qmk msys application 
  - cd `cd Desktop/qmk_firmware_q1_he/`
  - Run `make keychron/q1_he/ansi_encoder:default`
- Flash keyboard
  - Open qmk toolbox
  - Choose compiled `bin` file
  - Keyboard to bootloader - Remove cable from keyboard, hold escape, plug cable in
  - Click flash

