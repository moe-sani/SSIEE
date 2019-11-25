List of launch files
============

psm_one_rviz.launch: one PSM1 simulation
    
psm_exp.launch: don't know
psm_stable.launch: from WPI don't know

mtm_right_rviz.launch: only one MTMR simulation  
mtm_psm_rviz.launch: one MTMR + one PSM1 simulation  




    rostopic pub /dvrk/ss_davinci/state_joint_current sensor_msgs/JointState "header:
      seq: 0
      stamp: {secs: 0, nsecs: 0}
      frame_id: ''
    name: ["outer_roll", "outer_wrist_pitch", "outer_wrist_yaw", "jaw", "jaw_mimic_1", "jaw_mimic_2"]
    position: [0,0,0,0,0,0]
    velocity: [0,0,0,0,0,0]
    effort: [0,0,0,0,0,0]" -r 100


