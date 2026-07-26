# dynamixel_hardware_examples

> ## ⚠️ This repository is deprecated
>
> These examples are built on [`dynamixel_hardware`](https://github.com/dynamixel-community/dynamixel_hardware), which is deprecated in favour of ROBOTIS's officially maintained [`dynamixel_hardware_interface`](https://github.com/ROBOTIS-GIT/dynamixel_hardware_interface).
>
> - For an actively maintained OpenManipulator-X description built on the official hardware interface, use ROBOTIS's [`open_manipulator`](https://github.com/ROBOTIS-GIT/open_manipulator).
> - To convert your own robot description, read the [migration guide](https://github.com/dynamixel-community/dynamixel_hardware/blob/rolling/docs/migration_to_dynamixel_hardware_interface.md).
>
> This repository was never released to the ROS buildfarm and will be **archived (read-only)** once the `dynamixel_hardware` end-of-life status lands in `ros/rosdistro`. The descriptions below still work with a pinned `dynamixel_hardware`, but will receive no further fixes.

ros2_control robot examples with dynamixel_hardware

- `open_manipulator_x_description`: the reference implementation of the `ros2_control` robot using [ROBOTIS OpenManipulator-X](https://emanual.robotis.com/docs/en/platform/openmanipulator_x/overview/).

- `pantilt_bot_description`: the minimum implementation of the `ros2_control` robot using pan & tilt joints.
