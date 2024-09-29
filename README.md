# Learn to Identify Fundamental Sub-Tasks from One-Shot Video Demonstration of a Complete Task for Robot Execution #

**Introduction**
Robotic systems can significantly benefit from learning tasks through human demonstrations, especially when using videos captured by vision sensors. This capability is particularly important in improving complex, multi-step applications. Traditional methods often struggle to handle intricate patterns and tasks that span long time horizons, making it difficult to achieve precise task execution. However, classifying these complex tasks into manageable sub-tasks plays a critical role in fields such as computer vision, autonomous systems, and human-robot interaction. In the context of healthcare, where human-robot collaboration holds transformative potential, programming robots to perform complex and dynamic tasks remains a significant challenge. To address this, we propose a novel approach—a hybrid variance-based deep neural network (Hybrid V-DNN). Our model leverages transfer learning, incorporating a modified VGG-16 network to achieve enhanced performance. This hybrid model is designed to capture pixel-level variance in video frames and track hand movements, allowing for the segmentation of human actions into distinct sub-tasks such as reaching, grasping, placing, and retracting. By focusing on both pixel variance and human hand dynamics, the Hybrid V-DNN improves task segmentation accuracy, reduces computational overhead, and supports real-time processing. This approach not only enhances the robot’s ability to learn and execute dynamic tasks with greater precision but also opens up possibilities for more efficient, real-time robotic assistance in healthcare and other domains involving complex tasks.

## Preprocessing steps followed by our approach ##
![Preprosessing_flowchart](https://github.com/user-attachments/assets/f0e9d423-bab7-498a-a0c8-d448a4567372)

## Workflow for hybrid sub-task identification approach from any video demonstration. (HM represents hand movement.) ##
![Screenshot 2024-09-19 135630](https://github.com/user-attachments/assets/073c79a2-3160-452b-ae6b-d64a0fa7cc43)


  ## Experimental Results ##
To see the experimental results, please take a look at the given [YouTube link](https://www.youtube.com/watch?v=eaGPNka6EKo).
![task1](https://github.com/user-attachments/assets/85346aac-1852-4db2-b547-fdfe5a6d632c)
![task2](https://github.com/user-attachments/assets/e9e55308-4c2b-4d27-81c6-4b49279195f7)
![task 3](https://github.com/user-attachments/assets/a1c55923-b190-4c88-8617-ec2ac90d9805)
