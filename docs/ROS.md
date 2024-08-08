Here are a list of templates you can clone to your ROS workspace for faster development

1) fast_nav
contains:
a) navigation_handler.py
b) navigation_launch.py
c) nav2_params.yaml
d) waypoint_playback.py
dependencies:
fast_nav_interfaces.msg

2) mecanum_robot
contains:
a) fully configurable mecanum robot urdf along with lidar, camera, imu, and other sensor links
b) robot odom and tf broadcaster
c) robot_bridge.py with serial read and serial write


6) delta_omni_robot
contains:
a) fully configurable delta omni robot urdf along with lidar, camera, imu, and other sensor links
b) robot odom and tf broadcaster
c) robot_bridge.py with serial read and serial write

8) 
9) quad_omni_robot
contains:
a) fully configurable quad omni robot urdf along with lidar, camera, imu, and other sensor links
b) robot odom and tf broadcaster
c) robot_bridge.py with serial read and serial write


11) coaxial_swerve_robot
contains:
a) fully configurable coaxial swerve drive robot urdf along with lidar, camera, imu, and other sensor links
b) robot odom and tf broadcaster
c) robot_bridge.py with serial read and serial write

13) differential_swerve_robot
contains:
a) fully configurable differential swerve drive robot urdf along with lidar, camera, imu, and other sensor links
b) robot odom and tf broadcaster
c) robot_bridge.py with serial read and serial write

16) vision_genie
contains:
a) webcam and realsense frames grabbing nodes (wc_camera_node, rs_camera_node) 
b) frames processing code (templates include grabbing xy coordinates of object using yolo and caascade classifier)
c) camera data processing code (include follower code)
d) openpose detection template
e) qr code detection
f) aruco code detection

18) language_genie (mainly for robocup use only)
contains:
a) custom llama vla model template
