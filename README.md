# prusa_i3
This is for 3D printer

## Compile code and upload code by command
### Compile code and upload code by command
```
sudo arduino --board arduino:avr:mega:cpu=atmega2560 --port /dev/ttyUSB0 --upload /<the folder of prusa_i3>/Marlin.ino
```

### Compile code by command
```
arduino --board arduino:avr:mega:cpu=atmega2560  --pref build.path=/tmp/build --verify /<the folder of prusa_i3>/Marlin.ino
```

### Arduino_lib
If arduino can't work, please download https://github.com/Jumbo88888/arduino_lib.git.
At arduino_lib.git already fix dependent library. So arduino can work well.

## Code History

master - 13322c05c38116e134f857604a7f9df0ea8530de
The origin code no level function.

Reference:
- <a href="http://fkcsmart.blogspot.tw/2016/03/arduino-compile-code-and-upload-code-by.html">[Arduino][3DP]][Prusa i3] Compile code and upload code by command</a>
