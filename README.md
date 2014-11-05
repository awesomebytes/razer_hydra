razer_hydra
===============

ROS package for razer hydra motion controller. 
This is an unofficial driver which does NOT use the official Sixense SDK.

See documentation on the ros wiki: http://www.ros.org/wiki/razer_hydra

Be sure to execute "configure_udev_rules" before plugin in the Razer Hydra or it won't work.

Once launched with:
```roslaunch razer_hydra hydra.launch```

You should push some button of a paddle to wake them up (or at least I need to do it sometimes).

Check if there is output with:
```rostopic echo /hydra_calib```
