To save a calibration:

# To save camera-camera calibration:
rostopic pub /opt_calibration/action std_msgs/String "save" -1

# To save camera-world calibration:
rostopic pub /opt_calibration/action std_msgs/String "saveCam2WorldPose" -1