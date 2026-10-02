```bash
set $application_launcher pgrep wofi >/dev/null 2>&1 && killall wofi || wofi --show drun
bindsym $win+space exec $application_launcher

```
</br> 
![png](../assets/screenshotes/wofi.png)

