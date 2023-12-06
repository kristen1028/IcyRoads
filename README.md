# IceVision Intelligence

Project by Kristen Kane

<img src = "IcyRoads.png" width = "500" height = "500">

# Objective
IceVision Intelligence is meant to promote vehicular safety, offering cutting-edge artificial intelligence solutions designed to combat one of winter's most perilous hazards: icy roads. Our mission is to enhance road safety through advanced detection systems that alert drivers to the presence of ice, reducing the risk of accidents. 

<img src = "Icy Roads 1.png" width = "350" height = "350">
<img src = "Icy Roads 2.png" width = "450" height = "350">

[Icy Road Slides](https://docs.google.com/presentation/d/18Q3D1hVQ1lUIEyh8BX9vg-vuHmLc5DF_ei9m_K_i3oY/edit?usp=sharing)

# Impact 
### Enhanced Road Safety: 
By providing accurate real-time data on road conditions, the technology could drastically reduce the number of accidents caused by icy roads. This would not only save lives but also reduce the number of injuries and the associated healthcare costs.

### Economic Benefits: 
Fewer accidents mean less traffic disruption, which can lead to improved productivity as people and goods reach their destinations on time. Additionally, the reduction in accidents would decrease the burden on emergency services and the costs associated with road repairs and vehicle damage.

### Driver Confidence and Comfort: 
Knowing that their vehicle is equipped to alert them about icy conditions can reduce driver anxiety during winter months, potentially leading to a more pleasant and less stressful driving experience.

# What is AlexNet?
AlexNet is a deep learning model primarily known for its proficiency in image recognition tasks. It consists of several convolutional layers, pooling layers, and fully connected layers. The strength of AlexNet lies in its ability to extract complex features from images, making it suitable for varied and intricate visual recognition tasks.

## AlexNet Application in Ice Detection
### Image Data Collection:
Vehicles equipped with cameras and sensors would collect visual data of road surfaces in various conditions.
This data could include images of roads under different weather conditions, times of day, and varying levels of traffic.

### Pre-Processing:
The raw images would need to be pre-processed for optimal analysis. This includes resizing, normalizing, and potentially augmenting the images to ensure consistency in the input data.

### Feature Extraction:
AlexNet would analyze these images to identify features that are indicative of icy conditions. This could include patterns, textures, and color changes on the road surface.
The convolutional layers of AlexNet are adept at hierarchically extracting features, from basic edges and textures in the initial layers to more complex patterns in deeper layers.

<img src = "feature maps.png" width = "350" height = "350">

[Icy Roads Feature Maps](https://colab.research.google.com/drive/1p_u3RgqqhERl9GpCYy_fRvyMMO4TdCP2#scrollTo=mQb-EZfpq-N8)

### Classification:
After feature extraction, the network would classify the road condition based on the identified features. Essentially, it determines whether the image shows an icy road or not.
The final layers of AlexNet, which are fully connected, would be responsible for this classification task.

### Training and Validation:
To achieve accurate results, AlexNet would be trained on a large dataset of road images, both with and without ice. This training allows the network to learn the distinguishing characteristics of icy roads.
The model would be validated and tested on separate sets of images to ensure its reliability and accuracy in real-world conditions.

### Integration and Real-Time Analysis:
Once trained, the model would be integrated into IceVision Intelligence's system, where it would analyze real-time data from vehicle-mounted cameras.
For real-time processing, the model might need optimization for speed without significantly compromising accuracy.

### Feedback and Continuous Learning:
The system would also include a feedback mechanism, where incorrect predictions are analyzed and used for further training, allowing the model to adapt to new patterns and conditions over time.


## Diagram
<img src = "AlexNet Diagram.png" width = "500" height = "300">

# Results
The graphs below indicate the training accuracy and loss over the course of the training runs:
<img src = "W&B Chart 12_5_2023, 7_59_33 PM.png" width = "400" height = "250">
<img src = "W&B Chart 12_5_2023, 7_59_18 PM.png" width = "400" height = "250">

[Weights & Biases](https://wandb.ai/kristen-kane/Linear_Model_Photo_1/runs/rfc7hi1x?workspace=user-kristen-kane1028)

## Run Summary
<img src = "percentage" width = "550" height = "90">

81% accuracy

[Colab for Slides](https://colab.research.google.com/drive/1lhwRcUwioteRZCgMaxRkPD7NmHMk5TSE#scrollTo=_8N1vmLLA3Dr)

# Pose
[Pose Machine Colab](https://colab.research.google.com/drive/1FGiIFSl5hHhYGstDBIPDu5QLdALGaygl#scrollTo=9B57XS0NZPIy)

<img src = "MoveNet Example" width = "400" height = "250">

Integrating MoveNet in an ice detection system for vehicles can significantly enhance safety features, not only by detecting and reacting to external conditions like icy roads but also by monitoring and responding to human factors inside and outside the vehicle.

For more information contact: @kanek2022@fau.edu 
