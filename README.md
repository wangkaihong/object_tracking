Implementation of Object tracking

Given list of coordinates of objects in video, the program can identify their trajectory and visualize it.
![image](https://github.com/wangkaihong/object_tracking/blob/master/example/g48.jpg)

The model use alpha-beta algorithm to find the most possible next position for each point in current position, and them use hungarian algorithm to find the globally optimal solution

Implementation of hungarian algorithm is cited from and can be referenced to https://github.com/tdedecko/hungarian-algorithm.
