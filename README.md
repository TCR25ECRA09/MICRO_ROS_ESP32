# MICRO_ROS_ESP32
The ESP32 connects to Wi-Fi and a micro-ROS Agent, subscribes to the ROS 2 `/cmd_vel` topic, receives linear and angular velocity commands, computes left and right wheel speeds using differential drive kinematics, converts them into PWM signals, and controls two DC motors through an L298N motor driver for real-time robot movement.
