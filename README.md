# x11vnc

x11vnc.sh
```bash
# Export Display
export DISPLAY=:0

# Create the passwd only one time
[ ! -f ~/.vnc_passwd ] && x11vnc -storepasswd  ~/.vnc_passwd

# start x11vnc
x11vnc -many -rfbauth ~/.vnc_passwd
```
