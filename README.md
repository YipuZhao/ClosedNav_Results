### Devices
- Desktop (passmark 1639, 130W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Xeon+E5-2680+%40+2.70GHz&id=1221
- Laptop (passmark 2140, 15W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i7-8550U+%40+1.80GHz&id=3064

### Benchmark
- Gazebo simulation [http://gazebosim.org/tutorials?tut=ros_overview]

### VO/VSLAM/VINS Systems Assessed
- GF-ORB-SLAM Stereo + Inertial Fusion [https://github.com/YipuZhao/gf_orb_slam2]
- ORB-SLAM Stereo + Inertial Fusion [same as above]
- SVO Stereo + Inertial Fusion https://github.com/YipuZhao/rpg_svo
- VINS-Fusion https://github.com/YipuZhao/VINS-Fusion
- MSCKF Stereo https://github.com/YipuZhao/msckf_vio

Compared to the official repos, the baseline methods in my repo are with explicit logging on pose tracking and time cost.
