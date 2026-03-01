# Linux automatic check dual gpu for x11
A script that checks the number of GPUs and substitutes for X11 the settings defined for iGPU + discrete or only discrete
The script is being developed in order not to change the configuration yourself in case of gpu switching.
It is highly desirable to determine the settings for X11 yourself, since there is no magic tablet that would fix everything.

Templates must be in folder `/etc/X11/xorg.conf.d/templates`
- `hybrid.conf` - file for dualgpu
- `discrete.conf` - file for discrete only
