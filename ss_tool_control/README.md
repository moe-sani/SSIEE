
rostopic echo /joint_states

    header: 
      seq: 164
      stamp: 
        secs: 1574273922
        nsecs: 311703920
      frame_id: ''
    name: [joint_index_MIP, joint_middle_MIP, joint_thumb_MIP, joint_index_PIP, joint_middle_PIP,
      joint_thumb_PIP]
    position: [-0.00010471975584724902, -0.00010471975584724902, -3.926990744268499e-05, 0.0, 0.0, 0.0]
    velocity: []
    effort: []
    ---

---------

    rostopic pub /ss_tool/joint_states sensor_msgs/JointState "header:
      seq: 0
      stamp: {secs: 0, nsecs: 0}
      frame_id: ''
    name: ["joint_index_MIP", "joint_middle_MIP", "joint_thumb_MIP","joint_index_PIP", "joint_middle_PIP", "joint_thumb_PIP"]
    position: [0,0,0,0,0,0]
    velocity: [0]
    effort: [0]" -r 100
