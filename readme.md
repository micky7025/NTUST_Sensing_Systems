### Rename bag's name to NTUST(NTUST.bag, This file is unpublished)
roscore
### new term
roslaunch justrun.launch

-------------

rostopic echo /rgb/front_center/original_image

rostopic echo /radar/front_center/received_messages
### if u want to watch info of data, add
### "|grep encoding" for type 
