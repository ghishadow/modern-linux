# Useful Commands 

``` shell
$ journalctl -b 0 --grep "renderer for"

```


- check nvidia logs

``` shell
$ journalctl | grep nvidia | head

```


- check for LIBVA/VDPAU
``` shell 
$ env | grep -E "LIBVA|VDPAU"

```

- check Wayland display

``` shell
$ echo $WAYLAND_DISPLAY
```

- check system's current clock source
``` shell
$ cat /sys/devices/system/clocksource/clocksource0/current_clocksource
```
eg. tsc
