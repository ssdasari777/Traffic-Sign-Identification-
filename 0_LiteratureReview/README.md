# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:
Various machine learning techniques have been explored for traffic sign recognition. Most projects use Convolutional Neural Networks (CNNs) due to their strong image classification capabilities. Transfer learning with pretrained models like MobileNet, YOLO, and ResNet has proven effective. Additionally, Edge Impulse simplifies model deployment on embedded devices like Arduino and Raspberry Pi.

Summary of Each Work
Source 1: "Traffic Sign Recognition with CNNs"
Objective: To develop an image classification model for traffic sign recognition using CNNs.
Methods: A custom CNN model was trained on the German Traffic Sign Dataset (GTSRB).
Outcomes: Achieved 96% accuracy in identifying multiple traffic signs.
Relation to Project: This study confirms that CNNs are an effective approach for our problem.

Source 2: "TinyML for Real-Time Traffic Sign Detection"
Objective: To deploy a lightweight traffic sign classification model on microcontrollers using TinyML.
Methods: Used MobileNetV2 with Edge Impulse for on-device inference.
Outcomes: Demonstrated low-latency sign recognition on embedded devices with 80% accuracy.
Relation to Project: Shows that MobileNet + Edge Impulse is a viable approach for our TinyML-based deployment.

Source 3: "Transfer Learning for Traffic Sign Classification"
Objective: To improve accuracy with small datasets using transfer learning.
Methods: Used pretrained MobileNetV2 and fine-tuned it with a smaller traffic sign dataset.
Outcomes: Improved accuracy by 15% compared to training from scratch.
Relation to Project: This justifies our use of transfer learning to train our model efficiently.
