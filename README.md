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

Reference:
- <a href="http://fkcsmart.blogspot.tw/2016/03/arduino-compile-code-and-upload-code-by.html">[Arduino][3DP]][Prusa i3] Compile code and upload code by command</a>
