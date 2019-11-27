# SSIEE
SMARTsurg Integrated Exo-Eskeleton


This package is for simulating the 3-finger tool and davinci tool.


# How to run?

make sure to do the catkin_make in your workspace.

If you want to run this alongside the exoskeleton pipeline, follow the steps in hand_tracking package. but if you just want to see simulation, goto Joint Slide section
## 3finger tool

    roslaunch ss_3f_model ss_tool_rviz.launch
    
![Alt text](rviz.png?raw=true "Title")

## davinci tool

    roslaunch dvrk_model davinci_rviz.launch
    
![Alt text](davinci.png?raw=true "Title")


## Joint sliders

If you want to see the simulation by it self, you have to use it with joint sliders. to do so, you should pass the test parameter to the launch file.

    roslaunch ss_3f_model ss_tool_rviz.launch test:=true
    
![Alt text](rviz_slider.png?raw=true "Title")