## Build your Workspace

Creating the directory
```
mkdir -p dev_ws/src
```

Cloning the project
```
cd ~/dev_ws/src
git clone https://github.com/attu0/articubot_one.git

```

Colcon build
```
cd ~/dev_ws
colcon build --symlink-install

```

## Run the project

Source it
```
cd ~/dev_ws
source /opt/ros/humble/setup.bash
source install/setup.bash
```

ROS Run with empty world
```
ros2 launch articubot_one launch_sim.launch.py 
```
ROS run with My World
```
ros2 launch articubot_one launch_sim.launch.py world:=src/articubot_one/worlds/world.world 
```