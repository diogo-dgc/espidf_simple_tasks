# PlatformIO testing with ESP-IDF

![Static Badge](https://img.shields.io/badge/Framework-v.1.5.0--beta_(OUTDATED)-red)
![Static Badge](https://img.shields.io/badge/Code-OK_PASS-green)
![Static Badge](https://img.shields.io/badge/Hardware-ESP--8266-blue)

This sample use the Wemos D1 Mini board embedded ESP8266ex to develop RTOS calls to blink a LED each defined time and, parallel to this action, read a potentiometer on ADC every 20 ms.

> **IMPORTANT NOTICE:**<br/>Nowadays (Dec. 13rd 2023), PIO does not provide support for the most updated version of ESP-IDF (current 3.4 developed in April 8th 2021).<br/>There is a Issue opened since Jul 8th 2020 on platformio's Github about update ESP8266_RTOS_SDK v1.4.0 to ESP8266_RTOS_SDK v3.x.x (more details on https://github.com/platformio/platform-espressif8266/issues/219). Until now, there is no convention about the answer.<br/>The current version of RTOS_SDK provided by PIO is framework-esp8266-rtos-sdk @ 1.5.0-beta.5. You can see the version running a "Build” command.<br/>The version 1.5.0-beta is a very outdated SDK and ESPRESSIF does not provide any support - It can be result in unstable firmwares and no poor quality libraries from community. You can see document about the SDK v1.4.x on:
https://github.com/espressif/ESP8266_RTOS_SDK/tree/1.4.x/documents