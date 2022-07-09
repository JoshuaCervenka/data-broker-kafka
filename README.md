# Data Boker Arch Model:
![Demo_arch](https://user-images.githubusercontent.com/27900063/178113551-da534611-caa3-449d-b785-ab0f83b04d40.png)
This repo contains 2 demos to show off 2 different proof of concepts for brokering data across sensitivity levels. Each one leverages apache kafka using python to publish data, and subscribe to data while filtering the data from system high to system low. Each of the terminals on the left and right shown are AWS instances running CentOS, and the middle terminal is a proprietary Linux distro, also running in AWS

- image_demo_video demonstrates the strpping of EXIF metadata.
- Text_Demo_Video demonstrates a simple dirty-word search and strip
