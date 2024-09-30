# Learn to Identify Fundamental Sub-Tasks from One-Shot Video Demonstration of a Complete Task for Robot Execution #

## Introduction: ##
Robotic systems can significantly benefit from learning tasks through human demonstrations, especially when using videos captured by vision sensors. This capability is particularly important in improving complex, multi-step applications. Traditional methods often struggle to handle intricate patterns and tasks that span long time horizons, making it difficult to achieve precise task execution. However, classifying these complex tasks into manageable sub-tasks plays a critical role in fields such as computer vision, autonomous systems, and human-robot interaction. In the context of healthcare, where human-robot collaboration holds transformative potential, programming robots to perform complex and dynamic tasks remains a significant challenge. To address this, we propose a novel approach—a hybrid variance-based deep neural network (Hybrid V-DNN). Our model leverages transfer learning, incorporating a modified VGG-16 network to achieve enhanced performance. This hybrid model is designed to capture pixel-level variance in video frames and track hand movements, allowing for the segmentation of human actions into distinct sub-tasks such as reaching, grasping, placing, and retracting. By focusing on both pixel variance and human hand dynamics, the Hybrid V-DNN improves task segmentation accuracy, reduces computational overhead, and supports real-time processing. This approach not only enhances the robot’s ability to learn and execute dynamic tasks with greater precision but also opens up possibilities for more efficient, real-time robotic assistance in healthcare and other domains involving complex tasks.

## Preprocessing steps followed by our approach to create a custom dataset for model training ##
![Preprosessing_flowchart](https://github.com/user-attachments/assets/f0e9d423-bab7-498a-a0c8-d448a4567372)

## Workflow for hybrid sub-task identification approach from any video demonstration. (HM represents hand movement.) ##
![Screenshot 2024-09-19 135630](https://github.com/user-attachments/assets/073c79a2-3160-452b-ae6b-d64a0fa7cc43)

## The V-DNN Model architecture ##
The architecture of the V-DNN model is shown below.

![V-DNN_Model_architecture](https://github.com/user-attachments/assets/1e24c4d2-bf79-4bc5-9706-03340ab826c6)

**Hand Movement Recognition:**

The hand movement recognition frames are shown below in figure left to right (a)-HM1 (Reach), (b)-HM2 (Release), and (c)-HM3 (Retract) respectively.  

![Hand_moves](https://github.com/user-attachments/assets/487d8ac1-4e36-4fd3-aebe-2bef4c0e46d3)


## Experimental Results ##
To see the experimental results, please take a look at the given [YouTube link](https://www.youtube.com/watch?v=eaGPNka6EKo).

We can create many tasks using the learned subtasks. Below are five tasks that were created using the subtasks mentioned in the paper, demonstrated by humans and executed by robots, shown one by one.

![task1](https://github.com/user-attachments/assets/85346aac-1852-4db2-b547-fdfe5a6d632c)
![task2](https://github.com/user-attachments/assets/e9e55308-4c2b-4d27-81c6-4b49279195f7)
![task 3](https://github.com/user-attachments/assets/a1c55923-b190-4c88-8617-ec2ac90d9805)
![task 4](https://github.com/user-attachments/assets/6c6a5d5f-d9a7-4697-95b6-cb7fbe821f5c)
![task 5](https://github.com/user-attachments/assets/bd0036d7-af80-442e-ad61-b7492db0170d)

**The V-DNN model Accuracy and Loss graph:**

The V-DNN model accuracy and graph can be seen below.

![Model_accuracy_graph](https://github.com/user-attachments/assets/3dcb3332-246b-417f-89e5-0741b8415cf3)
![Model_loss_graph](https://github.com/user-attachments/assets/c3e4d493-7413-4213-9953-825813d006a5)


**The Kinova Gen3 robotic manipulator used in our approach for task execution**

![kinova](https://github.com/user-attachments/assets/cea28911-6c61-4d6b-b3bd-a6711f0f5a02)



