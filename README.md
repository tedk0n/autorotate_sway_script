# Autorotate_sway_script
Auto rotate bash script for sway.

Using the output of the monitor-sensor command (part of the iio-sensor-proxy package)  

Usage example
echo 'monitor-sensor | bash autorotate.sh &> autorotate.log' | at now
