# Assignment 2 Instructions:

The following assignment covers lectures 6, 7, 8 & 10 of irobman.

You are expected to answer all questions. The questions are of two types: theory and coding.

The marks for each part are specified in the `assignment_2.ipynb`. You are expected to attempt
questions in this ipython notebook and submit only this file in moodle.

There is no negative marking for incorrect answers.

You can attempt the assignment on both Linux or Mac-based systems.

## Setup

### Running Locally

The following packages are necessary for running locally:

Tested with `python==3.10` on Linux and `python==3.8.16` on Mac.

```shell
pip install numpy matplotlib filterpy open3d pybullet
```

## Known Issues:

- On Mac, the fps of `pybullet` will be quite slow.

- When using `open3d`, after a GUI window opens, make sure you close it before running the next code cell.

- In general, this assignment can run smoothly on Mac without Docker, but sometimes the GUI can hang up.