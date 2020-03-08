# dev_tools
Aliases, shortcuts, catkin_tools configs, etc. Anything that's useful for software development on the uWaterloo Robotics Team!

# Catkin Profiles
Included in `catkin_profiles` are profiles for `catkin_tools`. Assuming you've already installed [catkin_tools](https://catkin-tools.readthedocs.io/en/latest/), install these profiles:
```bash
cd <catkin_ws location>/.catkin_tools

# Delete profiles folder if one already exists
rm -rf profiles 

# Symlink to `catkin_profiles` folder so that profiles update when `dev_tools` is updated
ln -s -T <path to dev_tools repo>/catkin_profiles profiles
```
