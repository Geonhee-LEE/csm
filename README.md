For more information about the C(anonical) Scan Matcher, see the webpage: http://purl.org/censi/2007/csm .

This is the "master" branch of CSM, which uses GSL.

There is also another branch, called [``csm_eigen``][branch], which uses the ``eigen`` library. 
This branch is the work of people working at U. Freiburg and Kuka, including
Christoph Sprunk and Rainer Kuemmerle.

[branch]: https://github.com/AndreaCensi/csm/tree/csm_eigen

Binary install (via ROS melodic)
------------------------------

```
git clone https://github.com/AndreaCensi/csm
cd csm
move back cd ..
rosdep install --from-paths src --ignore-src -r -y
cd csm
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr/local .
make
sudo make install
cd ..
catkin_make
```
