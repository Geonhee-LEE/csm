For more information about the C(anonical) Scan Matcher, see the webpage: http://purl.org/censi/2007/csm .

This is the "master" branch of CSM, which uses GSL.

There is also another branch, called [``csm_eigen``][branch], which uses the ``eigen`` library. 
This branch is the work of people working at U. Freiburg and Kuka, including
Christoph Sprunk and Rainer Kuemmerle.

[branch]: https://github.com/AndreaCensi/csm/tree/csm_eigen

Binary install (via ROS melodic)
------------------------------

```
cd ~/catkin_ws/src
git clone https://github.com/AndreaCensi/csm
cd ..
catkin_make_isolated
cd ~/catkin_ws/src
git clone https://github.com/ccny-ros-pkg/scan_tools.git
cd ..
catkin_make_isolated
source devel/setup.bash
```
