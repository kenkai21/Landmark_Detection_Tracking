# Landmark_Detection_Tracking

This projects implements *graph-based SLAM* (Simultaneous Localization and Mapping), a robust method for tracking an object over time and building a map of the environment, This is achieved through the use of sensor and motion data and he exploitation elements of probability, motion models, and linear algebra.

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot.*

<p align="center">
	<img src="images/robot_world.png" align="middle" alt="drawing" width="500px">
</p>

## Project Structure
Execute sequentially

#### `robot_class.py`
__Notebook 1__ : Robot Moving and Sensing;

__Notebook 2__ : Omega and Xi, Constraints;

__Notebook 3__ : Landmark Detection and Tracking.

## Installation
```sh
$ git clone https://github.com/kenkai21/Landmark_Detection_Tracking.git
$ sudo pip3 install -r requirements.txt
```
## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
