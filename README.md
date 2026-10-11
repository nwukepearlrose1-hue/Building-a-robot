# Building a Robot in Gazebo

A simple differential-drive robot built from scratch in SDF for Gazebo (Jetty).

## What's in it
- Blue box chassis
- Red and green wheels (revolute joints)
- Cyan caster ball (ball joint)
- Ground plane and sun light

## How to run
1. Install [Pixi](https://pixi.sh) and Gazebo (`pixi add "libgz-sim=10"`).
2. In the project folder, run:

   pixi shell
   gz sim building_robot.sdf

3. Click **Play** at the bottom left so the robot settles onto the ground.

## Files
- `building_robot.sdf`: the world and robot definition
- `pixi.toml` / `pixi.lock`: environment setup
