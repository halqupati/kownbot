# KownBot 

KownBot is an autonomous differential drive robot with two wheels.

The following sections describe how to run the robot simulation and how to make use of the real hardware using the available package launch files.


### Gazebo Simulation with ROS Control

![Screenshot from 2023-10-13 02-47-35](https://github.com/halqupati/kownbot/assets/48286288/da5415f0-5397-4059-a4b8-8ccba13c23cc)

![Screenshot from 2023-10-13 02-57-20](https://github.com/halqupati/kownbot/assets/48286288/795db7df-bd84-4716-a7f6-0e162ee59d2c)

### Navigation

![Screenshot from 2023-10-13 03-04-43](https://github.com/halqupati/kownbot/assets/48286288/8043593e-2853-45ca-9d46-db3e515d5763)

## Usage
# Open 1th terminal
1. source workspace
```
. ~/{YOUR_WORKSPACE}/devel/setup.bash
 ```
3. Run gazebo simulition
   ```
   roslaunch kownbot_gazebo multi_kownbot_view.launch
   ```
# Open 2th terminal
1. source workspace
```
. ~/{YOUR_WORKSPACE}/devel/setup.bash
```
3. Run navigation
   ```
   roslaunch kownbot_navigation multi_kownbot_navigation.launch
   ```

## :wrench: Contributing

Your contributions are most welcome. These can be in the form of raising issues, creating PRs to correct or add documentation and of course solving existing issues or adding new features.


## :pencil: License

`kownbot` is licenses under the [BSD 3-Clause](./LICENSE).
See also [open-source-license-acknowledgements-and-third-party-copyrights.md](open-source-license-acknowledgements-and-third-party-copyrights.md).
