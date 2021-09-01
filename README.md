# Group-based-on-iteration

If you specifically want to do it inside a for each, this will work (metadata must be plugged into second input):

setpointgroup(0, sprintf("group_%i", int(detail(1, "iteration", 0))), @ptnum, 1, "set");

![屏幕截图 2021-09-01 180335](https://user-images.githubusercontent.com/63625631/131652747-9f2d24c8-b6a2-47fe-80d4-666ad1ba0a79.jpg)
