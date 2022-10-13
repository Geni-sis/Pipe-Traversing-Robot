# Pipe-Traversing-Robot
The purpose of this robot is to automize the maintainance and surveying of pipeline systems used in industries

1. The robot uses a screw mechanism to traverse through pipelines, this allowed for a smooth movement and stable footage even on turns and bumps
2. The robot uses an on-board camera to capture the inside of the pipe structure
3. The micro-controller (Raspberry-pi) uses the camera footage and applies "Canny edge detection" to detect crack and leaks in the pipe structure.
4. This data, crack location and a picture, is stored and later can be used for repair work.
