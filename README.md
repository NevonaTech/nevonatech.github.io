# Welcom to NevonaTech website

## NevonaTech web pages
1) Build the web pages in Flutter
2) Upload the web pages sources to nevonatech.github.io

## Firmware updates via OTA ("Over The Air")
1) Add the firmware binary image (e.g. sensor-fw-2.0.ino.bin)
2) Update OTA-update.json to specify the firmware URL and Version which will be pushed on the next reboot.

Example for JSON file that support multiple configurations
```
{
  "Configurations": [
    {
      "Board": "ESP32_DEV",
      "Version": "2.3",
      "URL": "https://nevonatech.github.io/OTA/sensor-fw-2.3.ino.bin"
    },
    {
      "Board": "ESP32_DEV",
      "Config": "4MB",
      "Version": "2.0",
      "URL": "https://nevonatech.github.io/OTA/sensor-fw-2.0.ino.bin"
    }
  ]
}
```

@copyright
