# Learn to Identify Fundamental Sub-Tasks from One-Shot Video Demonstration of a Complete Task for Robot Execution #

**Introduction**
Robotic systems can significantly benefit from learning tasks through human demonstrations, especially when using videos captured by vision sensors. This capability is particularly important in improving applications that involve complex, multi-step tasks. Traditional methods often struggle to handle intricate patterns and tasks that span long time horizons, making it difficult to achieve precise task execution. However, classifying these complex tasks into manageable sub-tasks plays a critical role in fields such as computer vision, autonomous systems, and human-robot interaction. In the context of healthcare, where human-robot collaboration holds transformative potential, programming robots to perform complex and dynamic tasks remains a significant challenge. To address this, we propose a novel approach—a hybrid variance-based deep neural network (Hybrid V-DNN). Our model leverages transfer learning, incorporating a modified VGG-16 network to achieve enhanced performance. This hybrid model is designed to capture pixel-level variance in video frames and track hand movements, allowing for the segmentation of human actions into distinct sub-tasks such as reaching, grasping, placing, and retracting. By focusing on both pixel variance and human hand dynamics, the Hybrid V-DNN improves task segmentation accuracy, reduces computational overhead, and supports real-time processing. This approach not only enhances the robot’s ability to learn and execute dynamic tasks with greater precision but also opens up possibilities for more efficient, real-time robotic assistance in healthcare and other domains involving complex tasks.

## Preprocessing steps followed by our approach ##
![Preprosessing_flowchart](https://github.com/user-attachments/assets/f0e9d423-bab7-498a-a0c8-d448a4567372)

## Workflow for hybrid sub-task identification approach from any video demonstration. (HM represents hand movement.) ##
![Screenshot 2024-09-19 135630](https://github.com/user-attachments/assets/073c79a2-3160-452b-ae6b-d64a0fa7cc43)


  _Experimental Results_
https://www.youtube.com/watch?v=eaGPNka6EKo


![Sub-task learning GIF](https://github.com/dharmi-123/Subaction-learning-from-V-DNN-Model/blob/main/R_task_1-ezgif.com-video-to-gif-converter.gif)
[Watch the video](https://github.com/dharmi-123/Subaction-learning-from-V-DNN-Model/blob/main/task%201.mp4)

