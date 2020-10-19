### READ.md

roslaunch rrt_exploration_201016  multiple_simulated.launch robot_count:=3

可以在这个文件中更改地图文件

robot1需要在地图的(0,0,0)点处

若要修改其他机器人的位置需要修改的文件有：

robot_tf_transform.launch

kobuki.launch.xml

initposes.launch



