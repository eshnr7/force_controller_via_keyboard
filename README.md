# Keyboard Force Controller

1. Create a new package in your workspace

```bash
  cd ~/catkin_ws/src
  catkin_create_pkg <package_name> std_msgs rospy ros_clients
  
  cd ~/catkin_ws
  catkin_make

```
2. Create a python file in your package and copy and paste navigator.py into it.

3. Don't forget to make the python file you just created executable

```bash
  chmod +x navigator.py
```

4. After launching the ros_scenario package, run this code

```bash
  rosrun <package_name> navigator.py
```
