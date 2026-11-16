# Hardware results

The newest result of each verb of the board exercise, by board type and firmware, with the date and the tool commit it ran against.

| Verb | nucleo-f767zi / zephyr_mcumgr | heltec-v4 / meshtastic | sparkfun-pro-micro-rp2040 / bare | raspberrypi-pico2w / zephyr_settings | raspberrypi-picow / zephyr_settings | adafruit-kb2040 / bare |
|---|---|---|---|---|---|---|
| `survey` | Yes 2026-11-15 `8105500` | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `da8bff2` |
| `plan` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` | **No** 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` |
| `diag` | Yes 2026-11-15 `8105500` |  |  | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `da8bff2` |  |
| `apply` | Yes 2026-11-15 `8105500` | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `d986bc8` | Yes 2026-11-16 `da8bff2` |
| `update-there-and-back` | Yes 2026-11-15 `8105500` | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | **No** 2026-11-16 `77c9087` | Yes 2026-11-16 `d986bc8` | Yes 2026-11-16 `da8bff2` |
| `came-back` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `77c9087` | **No** 2026-11-16 `77c9087` | **No** 2026-11-16 `d986bc8` | Yes 2026-11-16 `77c9087` |
| `facts` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `da8bff2` |  |
| `secrets` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `da8bff2` |  |
| `backup-regions` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `77c9087` |  |
| `backup-chip` |  | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `da8bff2` |
| `keys-export` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `77c9087` | **No** 2026-11-16 `77c9087` |  |
| `survey-deep` |  | Yes 2026-11-15 `8105500` |  |  |  |  |
| `restore-regions` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `d986bc8` |  |
| `snapshot-switch` |  | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `d986bc8` | Yes 2026-11-16 `da8bff2` |
| `keys-restore` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `d986bc8` |  |
| `erase-chip` |  | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-16 `da8bff2` | Yes 2026-11-15 `8aad45e` | Yes 2026-11-16 `da8bff2` |
| `erase-region` |  | Yes 2026-11-15 `8105500` |  | Yes 2026-11-16 `da8bff2` | **No** 2026-11-16 `d986bc8` |  |
| `family-switch` |  | Yes 2026-11-15 `8105500` | Yes 2026-11-16 `da8bff2` |  |  | Yes 2026-11-16 `da8bff2` |
| `reboot` |  |  |  | Yes 2026-11-16 `77c9087` | Yes 2026-11-16 `d986bc8` |  |
| `device-test` |  |  |  | Yes 2026-11-16 `77c9087` | **No** 2026-11-16 `77c9087` |  |
| `boot` |  |  |  | Yes 2026-11-16 `77c9087` |  |  |
