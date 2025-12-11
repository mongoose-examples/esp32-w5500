This project showcases a simple HTTP server using the [Mongoose Networking Library](https://mongoose.ws/u/s/arduino/397), which runs on a ESP32-C3-DevKitC board
connected to the W5500 Ethernet module.

## Notes

Open the `esp32.ino` file in your Arduino IDE. In the menu, select `Sketch` and choose `Verify/Compile` to build the firmware
and `Upload` to flash it.

The project is compatible with any ESP32 board, therefore the SPI pins for the W5500 module might differ. The pins are defined in `esp32.ino`
file and need to be modified if a different ESP32 board is used.

## Documentation and Tutorials

- [Tutorials](https://mongoose.ws/documentation/#tutorials)
- [Mongoose User Guide](https://mongoose.ws/documentation/)
