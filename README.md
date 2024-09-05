# IBED
A course-based badminton gesture recognition system using Arduino, C++, Python and provided a simple visualization UI with fun sound effects.
![image](https://github.com/Papripa/IBED/blob/main/UI.png)

The paper and PowerPoint are both included.
## Introduction
The project contains 4 parts:
1. Data preprocessing. We used [TinyMotionTrainer](https://experiments.withgoogle.com/tiny-motion-trainer) to collect 4 main gestures and clean the data. 
2. Model training. We designed a simple LSTM and leave-one-user-out model to train by Python. The code is in the ".ipy" file.
![image](https://github.com/Papripa/IBED/blob/main/model.png)

We can see the results with this model.

### Test performance
![image](https://github.com/Papripa/IBED/blob/main/Test.png)
### Confusion Matrix
![image](https://github.com/Papripa/IBED/blob/main/CM.png)
### Train performance
![image](https://github.com/Papripa/IBED/blob/main/Train.png)
4. Implemented the model on Arduino 33 BLE sense. We used the quantization technique and imported it to the board.
6. Designed the visualization and entertainment page with sound effects.
