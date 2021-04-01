# SLAM map my world

Directory structure:

<img width="436" alt="Screen Shot 2021-04-01 at 12 16 09 PM" src="https://user-images.githubusercontent.com/16000838/113264513-1a842a00-92e4-11eb-819d-a0a98d745a0d.png">


Build:
```
catkin_make

source devel/setup.bash

roslaunch my_robot world.launch
```

next terminal
```
source devel/setup.bash

roslaunch my_robot mapping.launch
```

next terminal
```
source devel/setup.bash

roslaunch my_robot teleop.launch
```

## instructions
- move the robot in the environment to create the Map

View the created map

```
rtabmap-databaseViewer ~/.ros/rtabmap.db
```

## results

![IMG-20210401-WA0106](https://user-images.githubusercontent.com/16000838/113343090-62389f00-9340-11eb-9d89-55963347c2ee.jpg)

![IMG-20210401-WA0107](https://user-images.githubusercontent.com/16000838/113343099-65cc2600-9340-11eb-8ee3-75bad88a0130.jpg)


