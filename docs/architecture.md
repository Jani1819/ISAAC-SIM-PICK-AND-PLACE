# Simple Architecture

```mermaid
flowchart TD
    A[Isaac Sim Panda] --> B[ROS 2 Jazzy]
    B --> C[MoveIt 2]
    C --> D[RViz 2]
    C --> E[pymoveit2]
    E --> F[Arm Controller]
    E --> G[Gripper Controller]
    F --> A
    G --> A
```

### In simple words

- **Isaac Sim**: shows and simulates the Panda.
- **ROS 2**: connects the different programs.
- **MoveIt 2**: plans robot movement.
- **RViz**: shows the robot and planning information.
- **pymoveit2**: sends the pick-and-place commands from Python.
- **Controllers**: move the simulated arm and gripper.
