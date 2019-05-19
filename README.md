# EECS106B Final Project
This repository contains the code for rehabilitation robotics from EECS106B final project. More details can be found on [Rehabilitation Robotics](https://rehabroboticsee106b.weebly.com/)。

## Configuration
Pykdl files are needed when running the self-designed controller.  We used the independently supported directory [sawyer_pykdl](https://github.com/rupumped/sawyer_pykdl).

## Usage
Record a trajectory

` $ rosrun intera_examples joint_recorder.py -f <position_file_name> -r 1 `
