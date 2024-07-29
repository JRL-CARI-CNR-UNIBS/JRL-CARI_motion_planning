# CARI_motion_planning

A collection of C++ libraries for motion planning developed by JRL CARI - CNR-STIIMA/UNIBS.

## Download and Install

This repository contains links to all the packages required for motion planning, developed by JRL CARI - CNR-STIIMA/UNIBS.

### Step 1: Install Common Dependencies

First, follow the instructions to download and install the [cnr_common](https://github.com/JRL-CARI-CNR-UNIBS/cnr_common) package.

### Step 2: Clone and Initialize Submodules

To install all the motion planning packages in your ROS1 workspace, clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/JRL-CARI-CNR-UNIBS/JRL-CARI_motion_planning.git 
```

### Step 3: Keep Submodules Updated

Ensure that the submodules are always up to date with the following command:

```bash
cd cd JRL-CARI_motion_planning
git submodule update --init --recursive
. update_submodules.sh

```

### Step 4: Build and Install
In your catkin workspace set `catkin config --install` and build with `catkin build -cs`.
