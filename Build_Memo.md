### Check List
Q1. How to confirm the C++ compilier? 

A1. using ```g++ -v --help 2>/dev/null | grep -E "^\s+\-std=.*$"```
![image](https://github.com/Joy-Zhang-0303/ORB_SLAM3/assets/48177679/9946a2a7-10b1-44df-b998-839191dfe9e6)

Q2. Ho to compile Pangolin

A2. Run the preparation bash file and then build.

Q3. How to Check OpenCV Version

A3. ```dpkg -l opencv*```
![image](https://github.com/Joy-Zhang-0303/ORB_SLAM3/assets/48177679/a76601a7-b8d9-4249-b4f2-db7422fb9a66)
But, Version >=4.4 is necessary

Q4. eigen3

A4. ```dpkg -l | grep eigen```
![image](https://github.com/Joy-Zhang-0303/ORB_SLAM3/assets/48177679/a10732c2-dcf2-4bf8-a715-f6547ad088e2)
