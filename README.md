# Bike Theft Detection System

## Overview
This project aims to enhance the security of bicycles, electric bikes, and scooters on college campuses by implementing a face detection lock system. It addresses the widespread issue of vehicle theft and aims to provide a more secure and controlled parking environment.

## Problem Definition
Vehicle theft, particularly of bikes and scooters, is a significant problem on college campuses. Our solution uses advanced computer vision technologies to improve security measures, thus enhancing the campus environment and reputation.

## Stakeholders and Beneficiaries
- ASU Students and staff affected by theft incidents
- Campus security team
- Broader college community

## Current Solutions and Issues
### Current Solutions
- Bicycles are typically secured in designated parking areas using traditional locks or access codes.

### Issues with Current Solutions
- Traditional locks are susceptible to picking or breaking.
- Access codes can be shared or compromised.
- Lack of accountability for who accesses the parking areas.

## Proposed Solution
### End-to-End Product Solution
- Install locks equipped with cameras and a facial recognition model on each bicycle stand on campus.
- Users register through a mobile application and store their photo in a database.
- To unlock the bike, the user must have their face recognized by the system, which compares it to the stored photo.

### Computer Vision (CV) Solution
- **MTCNN (Multi-Task Cascaded Convolutional Neural Network)**: Detects faces in an input image.
- **InceptionResNetV2**: A deep CNN architecture used for extracting face encodings, which are then used for face recognition.

## Limitations and Risks
### Accuracy Issues
- Performance can be affected by lighting conditions, angles, or obstructions like masks or caps.

### Privacy Concerns
- Storing and handling facial recognition data requires compliance with privacy regulations and careful security measures.

### Cost
- Implementing and maintaining a CV-based security system involves significant hardware and software investment.

## References
- [InceptionResNetV2 Deep Learning Model](https://www.mathworks.com/help/deeplearning/ref/inceptionresnetv2.htm)
- [Using Inception Model for Image Recognition](https://www.indusmic.com/post/how-to-use-inception-model-for-image-recognition)
- [Multi-Task Cascaded Convolutional Neural Network (MTCNN)](https://medium.com/the-modern-scientist/multi-task-cascaded-convolutional-neural-network-mtcnn-a31d88f501c8)
- [Face Recognition in Python](https://www.javatpoint.com/face-recognition-in-python)
