# ESP CN105 Configuration

This is a repository to hold an example of how to setup your CN105 Mitsubishi ESPHome device to go alongside my YouTube video: https://youtu.be/I7jC5Xi063E

This is based on the project here: https://github.com/echavet/MitsubishiCN105ESPHome

**See the above repository for much more in-depth customization and guidance**

## Setup Instructions
### First time
```
1. python3 -m venv esphome_venv
2. source esphome_venv/bin/activate
3. pip install esphome
4. esphome clean main.yaml && esphome compile main.yaml
5. ls -la /dev/tty.*
6. esphome upload main.yaml --device /dev/tty.usbmodem101
```
---

### Re-entry
```
1. source esphome_venv/bin/activate
2. esphome clean main.yaml && esphome compile main.yaml
3. esphome upload main.yaml --device /dev/tty.usbmodem101
```