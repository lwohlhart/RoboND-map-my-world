# RoboND-map-my-world

```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/lwohlhart/slam_project.git
cd ..
catkin_make
source devel/setup.bash
```

install required dependencies by
```
rosdep install --from-paths slam_project
```

to launch the project execute the following commands in seperate terminal windows

```
roslaunch slam_project  world.launch world_file:=/home/workspace/catkin_ws/src/slam_project/worlds/factory_room.world

roslaunch slam_project teleop.launch

roslaunch slam_project rtabmapviz.launch

roslaunch slam_project mapping.launch
```

the resulting map databases of two provided environments can be downloaded here

mapping result for factory kitchen dining
https://drive.google.com/file/d/1VVCpNJqbN68czs2tuCf4eO4ZA71hlbG3/view?usp=sharing

mapping result for factory room
https://drive.google.com/file/d/1LaAt-BkkA_ElU2PFdP4EnEH0_WhoaUIv/view?usp=sharing


