# Hardware

## Block Diagram

Xtron Pro is composed of core and gamepad, the core is the programmable unit, and the gamepad is a peripheral. when they are connected together, it becomes a programmable game console, The core can be connected to the gamepad in two ways, portrait and landscape, so you can build games in either orientation.

The core can also work alone, and it can be turned into a watch after putting on the silicone shell, you can make your own watch applications.

There is an 8-pin pogopin connector on the back of the core. In addition to the handle, it can also connect to many other peripherals.

![](_static/xtronpro-system.png)

## Specifications

| Specifications      | Description                                       |
| ------------------- | ------------------------------------------------- |
| **MCU**             |                                                   |
| Model               | STM32F412                                         |
| Frequency           | 100MHz                                            |
| **SRAM**            |                                                   |
| Size                | 256KB                                             |
| **Flash**           |                                                   |
| Size                | 1MB                                               |
| **Extenal Flash**   |                                                   |
| Capacity            | 128M-bit                                          |
| SPI Clock           | 133MHz                                            |
| **RTC IC**          |                                                   |
| Model               | DS1330                                            |
| Backup Battery      | 0.3F Super Capacitance                            |
| **IMU**             |                                                   |
| Model               | MPU6887                                           |
| Gyroscopes Range    | \+/\- 2000 °/s                                    |
| Accelerometer Range | \+/\- 16g                                         |
| **Screen**          |                                                   |
| Type                | TFT                                               |
| Size                | 1.8"                                              |
| Resolution          | 160 x 128                                         |
| **Size**            | 82 x 53 x 22 mm                                   |
| **Button**          | 2 Touch Buttons, 8 Physical Buttons               |
| **Vibration Motor** | 14000 rpm                                         |
| **Speaker**         |                                                   |
| Type                | Moving Coil                                       |
| Rated Power         | 0.7W                                              |
| **Radio Module**    |                                                   |
| Model               | ESP32                                             |
| PSRAM               | 64M-bit                                           |
| Flash               | 16M-bit                                           |
| **Micophone**       |                                                   |
| Model               | 4015                                              |
| Sensitivity         | -30dB                                             |
| Directivity         | Omnidirectional                                   |
| **Connectors**      | USB-C, 4PIN Port, 8PIN Pogopin, Jacdac Phone Jack |
| **Battery**         | Lipo, 500mAh                                      |
| **Weight**          | 70g                                               |

## Diagram

1. The Core
2. The GamePad
3. Power button
4. Reset button
5. Light sensor
6. LED indicator
7. C button
8. Menu Button
9. Direction buttons
10. A, B buttons
11. Pogopin connector
12. USB Type-C
13. I2C connector
14. Jacdac connector