# Panda URDF / Xacro

The Panda robot is described using URDF/Xacro.

## Main arm links

```text
panda_link0
panda_link1
panda_link2
panda_link3
panda_link4
panda_link5
panda_link6
panda_link7
panda_link8
```

## Main arm joints

```text
panda_joint1 ... panda_joint7
```

## Gripper

```text
panda_hand
panda_leftfinger
panda_rightfinger
panda_finger_joint1
panda_finger_joint2
```

The project uses:

```xml
package://moveit_resources_panda_description/...
```

for the Panda robot meshes and description.

The MoveIt configuration connects this robot description to planning, RViz and ROS 2 controllers.
