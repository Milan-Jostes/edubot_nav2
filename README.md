<h2>Run Nav2 on Simulator with Gazebo</h2>
<p>Headless determines whether Gazebo will launch it's visual component</p>

```ros2 launch edubot_nav2 nav2_test.launch.py headless:=False```

<h2>How to fix launching issues:</h2>
<h3>Installl Cyclonedds</h3>

```sudo apt install ros-jazzy-rmw-cyclonedds-cpp```

<h3>Add this line to bashrc:</h3>

```export RMW_IMPLEMENTATION=rmw_cyclonedds_cpp```
