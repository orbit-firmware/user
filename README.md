# Example Orbit Keyboard setup

📖 [Docs](https://orbit-firmware.github.io/orbit)

The important files are:
 - `keyboard.toml` - keyboard configuration
 - `custom.rs` - can be used to extend keyboard functionality (optional)
 - `keymap.orbit` - Your own keymap (not used for compile process)

 These files will be placed in the `user` directory of the firmware.  
 If present they will be available in the compile process.

 Orbit also works with github actions, an example configuration can be found [here](https://github.com/orbit-firmware/example/blob/master/.github/workflows/build.yml).

 The action will provide you with the compiled firmware for your keyboard.
 Once flashed, you can drag your `keymap.orbit` onto the flash drive of the keyboard.