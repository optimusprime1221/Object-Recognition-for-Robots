# Object-Recognition-for-Robots

Introduction:
Object recognition is a fundamental capability in modern robotics systems which
enables to categorize objects in their environment and perform tasks such as grasping,
navigation, human-robot interaction, etc. This report shows two major algorithms
in computer vision: Deep Learning using Convolutional Neural Networks
(CNN) and Traditional Computer Vision using Local Features and Bag-of
Visual-Words (BoVW) with ORB descriptors.


StateoftheArtinComputerVision for Robotics:
• Modern Approaches
Contemporary robotics vision uses: CNNs for segmentation, classification and
detection[4], Transformers for object detection and pose estimation[5], Self
supervised learning for low-label environments[7]. Multimodal RGB-D
fusion networks for grasping and environment understanding[6].
6
• Deep Learning in Robotics
Advantages: Learns features directly from data and is robust under real-world
variations, scales with dataset size and integrates seamlessly with control and
planning pipelines through end-to-end learning.
Challenges: Requires large datasets, high compute cost and difficult to interpret; May fail under domain shift.




Conclusion:
This report implemented and compared two object recognition systems for robotic
perception: ResNet-18 CNN, achieving 99.9% accuracy, robust and modern and
ORB + BoVW +SVM,achieving 94% accuracy, efficient but limited .
Deep learning clearly outperforms classical methods because RGB-D images
contain significant appearance variation that CNNs model more effectively. Classical
methods remain educationally valuable and computationally lightweight, but are far
from state-of-the-art
