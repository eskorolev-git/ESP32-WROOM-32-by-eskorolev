# ESP32-WROOM-32 Proteus Library (Schematic Symbol Only)

A schematic symbol of the ESP32-WROOM-32 DevKit (38-pin) for **Proteus**.

<img width="496" height="742" alt="Screenshot 2026-10-10 at 6 10 31 PM" src="https://github.com/user-attachments/assets/95f5c4cc-d92a-4479-b478-25f890cf5b94" />

> **Limitations: please read before downloading**
> - **No PCB footprint.** You cannot use this part for PCB layout.
> - **Not simulatable.** It has no simulation model. It is a drawing with pins, nothing more.
>
> Use it to draw schematics and document your designs. If you need a part that simulates, look for a library that includes a VSM model.

## Details

| | |
|---|---|
| Device name | `ESP32-WROOM-32` |
| Library file | `ESP32_SYMBOL.lib` |
| Category | Microcontroller |
| Sub-category | ESP32 |
| Pins | 38 |
| Reference prefix | `U` |
| Tested on | Proteus 8 Professional |

## Installation

1. Download `ESP32_SYMBOL-eskorolev.zip` from this repository.
2. Extract
3. Copy `ESP32_SYMBOL.lib` into your Proteus library folder:
   `.../Labcenter Electronics/Proteus Professional/DATA/LIBRARY`
3. Restart Proteus.
4. In the schematic editor press **P** (Pick Devices) and search for `ESP32-WROOM-32`.

## Pin list

Pin numbers run 1 to 19 down the left side and 20 to 38 down the right side, top to bottom.

**Left side**

| No. | Name | Notes |
|---|---|---|
| 1 | 3V3 | Power |
| 2 | EN | Enable |
| 3 | VP | GPIO36 |
| 4 | VN | GPIO39 |
| 5 | 34 | GPIO34 |
| 6 | 35 | GPIO35 |
| 7 | 32 | GPIO32 |
| 8 | 33 | GPIO33 |
| 9 | 25 | GPIO25 |
| 10 | 26 | GPIO26 |
| 11 | 27 | GPIO27 |
| 12 | 14 | GPIO14 |
| 13 | 12 | GPIO12 |
| 14 | GND | Ground |
| 15 | 13 | GPIO13 |
| 16 | D2 | GPIO9 |
| 17 | D3 | GPIO10 |
| 18 | CMD | GPIO11 |
| 19 | 5V | Power |

**Right side**

| No. | Name | Notes |
|---|---|---|
| 20 | GND | Ground |
| 21 | 23 | GPIO23 |
| 22 | 22 | GPIO22 |
| 23 | TX | GPIO1 |
| 24 | RX | GPIO3 |
| 25 | 21 | GPIO21 |
| 26 | GND | Ground |
| 27 | 19 | GPIO19 |
| 28 | 18 | GPIO18 |
| 29 | 5 | GPIO5 |
| 30 | 17 | GPIO17 |
| 31 | 16 | GPIO16 |
| 32 | 4 | GPIO4 |
| 33 | 0 | GPIO0 |
| 34 | 2 | GPIO2 |
| 35 | 15 | GPIO15 |
| 36 | D1 | GPIO8 |
| 37 | D0 | GPIO7 |
| 38 | CLK | GPIO6 |


## License

Released under the MIT License. See [LICENSE](LICENSE).

The symbol drawing and pin layout are original work. ESP32 and ESP32-WROOM-32 are trademarks of Espressif Systems; this project is not affiliated with or endorsed by Espressif.

## Contributing

Found a wrong pin name or number? Open an issue or a pull request.
