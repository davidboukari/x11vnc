# x11vnc

```bash
# Export Display
export DISPLAY=:0

# Create the passwd
x11vnc -storepasswd  ~/.vnc_passwd

# start x11vnc
x11vnc -many -rfbauth ~/.vnc_passwd
```
