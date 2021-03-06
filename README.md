# Learning Grasping with Self-Supervised Deep Reinforcement Learning

![example workflow](https://github.com/kuolunwang/Grasping-with-SSDRL/actions/workflows/main.yml/badge.svg)

This repo is final project for 2021 Deep Learning and Practice class

teacher : 陳永昇、吳毅成、彭文孝

---

## clone repo
```
     $ git clone --recursive git@github.com:kuolunwang/Grasping-with-SSDRL.git
```

*You should run this code on a GPU computer*

---

## Building docker image
```
     $ cd Docker && source build.sh
```

## How to run
```
    $ cd Docker && source docker_run.sh
    Docker $ cd Grasping-with-SSDRL && source catkin_make.sh
    Docker $ source environment.sh
```

## If you want to enter same container
```
    $ cd Docker && source docker_join.sh
    Docker $ cd Grasping-with-SSDRL && source environment.sh
```

## Online learning
```
     $ roslaunch arm_bringup ur5.launch
     $ rosrun algorithm main.py
```
