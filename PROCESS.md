# Setup

Steps to get MicroPython running on the ESP32.

## 1. Flash MicroPython Firmware

- [ ] Install [`esptool`](https://github.com/espressif/esptool)

  ```bash
  pip install esptool
  ```

- [ ] Download the ESP32 [MicroPython firmware](https://micropython.org/download/)
- [ ] Erase the ESP32 flash with `esptool`
- [ ] Flash the firmware to the ESP32
- [ ] Install `mpremote`

    ```bash
    pip install mpremote
    ```

- [ ] Run `mpremote` to access the connected ESP32. You should enter the REPL.
