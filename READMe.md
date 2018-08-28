# Udacity RoboND - Project 4: Deep Learning - Follow Me
---

### Hardware Setup
Case
Motherboard
Intel CPU
2 Nvidia 980Ti GTX
Samsung 950 M.2
1 Samsung 2TB SSD
4 Western Digital 4TB Hard Drivews

### Software Setup
Windows 10, CUDA 8.0, Cudnn 7.12

Anaconda with Python 3.5.2   
Environment.yml  
pip uninstall tensorflow  
pip install tensorflow-gpu==1.3.0

### What are we trying to do
---

Would not work for cats, dogs, etc..

### Network
---

Output
Decoder
Decoder
Decoder
Conv
Encoder
Encoder
Encoder
Conv
Inputs


### Hyperparameters
---
rearning rate
epochs
batch_size
steps
steps_per_validation
workers

### Results
---
There are three different predictions available from the helper code provided:  

    patrol_with_targ: Test how well the network can detect the hero from a distance.
    patrol_non_targ: Test how often the network makes a mistake and identifies the wrong person as the target.
    following_images: Test how well the network can identify the target while following them.
    
    number true positives: 539, number false positives: 0, number false negatives: 0
    number true positives: 0, number false positives: 38, number false negatives: 0
    number true positives: 131, number false positives: 3, number false negatives: 170
    
    weight | 0.7604994324631101
    final_iou | 0.5452292991525213
    final_score | 0.4146465725677517
    
    

### Future Enhancements
---
    1 Collect more data
    2 Pooling layers, dropout
    3 Deeper layers (more memory)
