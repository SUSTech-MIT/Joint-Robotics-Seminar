# SUSTech-MIT Joint Robotics Seminar

Following our last meeting during the SUSTech-MIT Joint Workshop in August, 2020, this repository has been created to share research and educational collaborations presented at the joint robotics seminar, hosted by Prof. Harry Asada. 

# First SUSTech-MIT Joint Robotics Seminar
MIT: Friday, 10/16/2020, at 8:00 PM
SUSTech: Saturday, 10/17/2020, at 8:00 AM
 
## Talk 1 : 8:00 AM/PM – 8:30 AM/PM (Including discussion)
 
Title: Applying Findings from Human Motor Control Research to Robotics
 
Presenter: James Russell Hermus, MIT

Resources: [LINK TO BE UPDATED]
 
Abstract: Our lab strives to understand human physical interaction. Several ongoing SUSTech-MIT robotics projects also work with humans. I will discuss principles which guide our human research and a specific application. Humans are incredibly dexterous and excel at physical interaction with complex objects, despite large feedback delays, and many degrees of freedom. To accomplish such performance, we hypothesize that motor behavior is constructed using a limited set of primitive dynamic behaviors or “building blocks”, including oscillations, submovements, and mechanical impedances. One of the many added benefits of impedance, as a building "block”, is that impedances can be linearly super imposed. The control of kinematically redundant robots is often approached using nullspace projection methods. This is because, in theory, nullspace projections eliminate any conflict between primary and secondary tasks -- while impedance super-position does not. Experiments were run with a 7-DOF Kuka LBR which interacted with a circular constraint. When there was a large nullspace between the primary and secondary task, impedance super-position resulted in a comparable or smaller task conflict than conventional nullspace projection. In conclusion, while we are still striving to learn more about human motor control, dynamic motor primitives, specially impedance super-position, maybe useful for other SUSTech-MIT collaborators. 
 
## Talk 2: 8:30 AM/PM – 9:00 AM/PM (Including discussion)
 
Title: Fuse Sequential 3D Gaze and Environmental Context to Predict Foot Placements for Assistive Walking
 
Presenter: Dr. Kuangen Zhang, SUSTech

Resources: [LINK TO BE UPDATED]
 
Abstract: Humans usually look ahead and predictively tailor their foot placements on rough terrains, where eligible foot placements are limited. However, the vision-locomotion loop of amputees is broken, which makes the non-rhythmic locomotion on rough terrains challenging for amputees.
 
Previous studies have utilized environmental context to improve the control of the prosthesis in structured environments, where the transition is infrequent and usually a binary classification problem: remaining the current mode or switching to another mode. Conversely, transition on rough terrains happens every step and is a multi-class classification problem: selecting a suitable foot placement from multiple alternatives, which is difficult to predict with only the environmental context.
 
To address the above issue, this study proposes to fuse sequential 3D gaze and environmental context to predict foot placements of subjects. After fusing the gaze direction estimated by the eye-tracker and the point cloud measured by the red-green-blue-depth (RGBD) camera, the 3D gaze can be estimated more accurately than the triangulation provided by the eye-tracker. The head motion is estimated based on a simultaneous location and mapping (SLAM) algorithm to fuse sequential 3D gaze data and environmental point cloud.  Eligible footholds are extracted by segmenting the point cloud. Then the most possible foot placement at the next step is estimated by fusing the sequential 3D gaze and the segmented environmental context. Experimental results show that the gaze distance can be estimated with an error of 3 cm and the foot placements can be predicted accurately (95\%) before 0.5 step.
 
These results indicate that the 3D gaze and environmental context can be used to predict the foot placements, which is beneficial for studying the vision-locomotion loop of human and predictively controlling wearable robots.
 
# November seminar: 11/13
MIT: Morning 9:00 AM, Friday 11/13
SUSTech: Evening 8:00 PM, Friday 11/13
 
# December seminar: 12/18
MIT: Morning 9:00 AM, Friday 12/18
SUSTech: Evening 8:00 PM, Friday 12/18
