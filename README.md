<div align="center">

# RFID Access Control System — Arduino

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://arduino.cc)

*A contactless door access control system using RFID cards — grants or denies entry based on a whitelist of authorised card UIDs.*

</div>

---

## How it works

```
RFID card tap → RC522 reader → UID extracted → Whitelist check
                                              → Authorised: relay unlocks + green LED
                                              → Denied: buzzer + red LED
```

---

## Features

- MFRC522 RFID reader over SPI
- UID-based whitelist (easily extendable)
- Relay-controlled door lock
- LED + buzzer feedback for access granted/denied
- Serial log of all access attempts

---

## Hardware

`Arduino Uno` · `MFRC522 RFID Module` · `RFID Cards/Fobs` · `Relay` · `LEDs` · `Buzzer`

---

## Tech stack

`C++` · `Arduino IDE` · `MFRC522 library`

---

<div align="center">
<a href="https://github.com/Yami1106">Ashish Sukumar</a>
</div>
<!-- -->
