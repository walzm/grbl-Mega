![GitHub Logo](https://github.com/gnea/gnea-Media/blob/master/Grbl%20Logo/Grbl%20Logo%20250px.png?raw=true)

Flash from Raspberry PI using avrdude

```
avrdude -P /dev/ttyACM0 -p m2560 -D -c stk500v2 -V -U flash:w:-:i < grblUpload.ino.mega.hex
```
