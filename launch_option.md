## Launch option

go through steam library and find your cs2 and go to your game options and paste this

```bash
env -u LD_PRELOAD gamescope -w 1280 -h 960 -S stretch -f --force-grab-cursor -- env LD_PRELOAD="$LD_PRELOAD" %command% -novid
```

reasons:

1.  proper mouse capture
2.  fixes the the steam overlay & stuttering
3.  no up-scaling blur
4.  correct screen resolution based on pro-player like zywoo,donk,etc.
