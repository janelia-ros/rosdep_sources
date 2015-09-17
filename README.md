rosdep_sources
==============

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

##Installation

```shell
sudo apt-get install git
mkdir ~/git
cd ~/git
git clone https://github.com/janelia-ros/rosdep_sources.git
sudo cp ~/git/rosdep_sources/19-janelia.list /etc/ros/rosdep/sources.list.d/19-janelia.list
sudo rosdep init
rosdep update
```
