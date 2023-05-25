# Useful Commands 

```
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


