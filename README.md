# AI-Project

## Abstract

The relationship between vision and languages is important in our daily life. There are many researches concerning making computers to describe human actions such like Video Captioning, text to image or video. When it comes to human motion, there are fewer researches. The Task “Motion to description” is difficult, not to mention the task “Motion to detailed descriptions such as body parts”. Also, those researches about motion analysis mostly based on the joints connected with skeletons.

However, we think that the relationships between the disconnected joints are also important to motion analysis. Furthermore, movement of one part of the body that leads to a change in the overall posture, such as kicking with a leg to transition the entire body into an attacking stance. In order to consider such motion, the skeleton graph will need to consider the relationship between joints in different time.   

Additionally, the skeleton graph will consider the joints across all body parts instead of the joints within the single body part.

## Framework



We use Kinetics dataset.It is a large-scale, high-quality dataset for human action recognition in videos. The dataset consists of around 500,000 video clips covering 600 human action classes with at least 600 video clips for each action class. Each video clip lasts around 10 seconds and is labeled with a single action class. The videos are collected from YouTube. We use this 3D skeletons extracted by each frame in Kinetics by Openpose and run st-gcn.

## Result
