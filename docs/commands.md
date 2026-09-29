# Commands

## RViz + MoveIt

```bash
source /opt/ros/jazzy/setup.bash
source ~/ws_moveit2/install/setup.bash
source ~/TUT13/panda_moveit_config/install/setup.bash
ros2 launch panda_moveit_config demo.launch.py
```

## Pick and place

```bash
source /opt/ros/jazzy/setup.bash
source ~/ws_moveit2/install/setup.bash
source ~/pymoveit2_ws/install/setup.bash
source ~/TUT13/panda_moveit_config/install/setup.bash
python3 ~/pymoveit2_ws/src/pick_place/scripts/pick_place.py
```

## Check Panda package

```bash
ros2 pkg list | grep panda_moveit_config
```

## Check MoveIt Panda description

```bash
ros2 pkg list | grep moveit_resources
```

## Check controllers

```bash
ros2 control list_controllers
```

## Check joint values

```bash
ros2 topic echo /joint_states
```

## Check pymoveit2

```bash
python3 -c "import pymoveit2; print(pymoveit2.__file__)"
```
