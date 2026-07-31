# Change log

## Explicit hardware parameters (2026-07-31)

Base commit: `2295b215d0b86da37dcc6e71537d6a0b200d2adf` (`Update explicit parameters into de xacro`).

The 2FG7 wrapper exposes `robot_ip`, `interpreter_port`, `gripper_plugin`, and `tool_index` explicitly while retaining the previous defaults. The active joint remains the prismatically controlled `left_finger_joint`; the right finger remains its mimic joint.
