# Non-Contact Tactile Perception for Hybrid-Active Gripper

This work presents a novel approach to object recognition using a reconfigurable gripper with multiple Time of Flight (ToF) sensors attached to in fingers and palm, introducing the concept of  Non-Contact Tactile Perception. The approach aims to promote the proprioceptive sense in the gripper workspace allowing the object prediction to manipulation tasks.

The Hybrid-Active (H-A) Gripper can adapt its topology to achieve an optimal pick-up and gripping over different objects, which requires a reliable object estimation. The Non-Contact Tactile Perception uses the ToF sensors and the gripper reconfiguration degrees-of-freedom for the 3D perception and surface estimation of pick-up object. The gripper is an active agent in the manipulation system because when the object is recognized by it, the gripper becomes the master assigning commands and goals to the manipulator. The method is based on five ToF sensors in the palm that identify the distance and adjust the gripper to the object's center through its capability of managing the manipulator.

The H-A Gripper also has twelve sensors distributed over its three fingers: four sensors on each finger, two on the distal phalanx, and two on the middle phalanx. Fingers have rotational mobility of 180º, allowing sensing of all faces of the object and at different angles to the tridimensional reconstruction. 
The proposed approach is evaluated in four experiments that analyze the influence of resolution, object complexity, finger tilt, and angular sampling over eleven objects with different complexities. The experimentation set allows the overall evaluation of Non-Contact Tactile Perception and the specification of its performance parameters.


Below we have the H-A Gripper scanning a sphere, on the left a video using the front view and on the right the top view. 

<img src="https://github.com/jonathashmp/H-A-Gripper/blob/main/Videos/front_video.gif" width=40% height=40% /> <img src="https://github.com/jonathashmp/H-A-Gripper/blob/main/Videos/top_video.gif" width=50% height=50% />

## Instructions

