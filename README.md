# face-recognition


This is a python project regarding "Face recognition" and subtopic covers "Drowsiness detection".
The major aim of this project is to develop a drowsiness detection system by monitoring the eyes. it is believed that the symptoms of driver fatigue can be detected early enough to avoid a car accidents. In such a case when drowsiness is detected, a warning signal is issued to alert the driver. This detection system provides a noncontact technique for judging different levels of driver alertness and facilitates early detection of a decline in alertness during driving. In such a case when fatigue is detected, a warning signal is issued to alert the driver. The system also has additional feature of slowing down the vehicle, if driver fails to respond to the alarm and ultimately stops the vehicle. In this Python project, we will be using Opencv for  gathering the images from webcam and feed them into a machine Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’.


## Modules to be installed using pip 


     pip install opencv
     pip install os
     pip install keras
     pip install mixer
     pip install pygame
     
## Modules using pip3

     pip3 install opencv
     pip3 install os
     pip3 install keras
     pip3 install mixer
     pip3 install pygame

## output at active state
![2](https://user-images.githubusercontent.com/105065454/170833367-a3f01e02-3cc4-4e34-885e-800ab60b877c.jpeg)


## output at low drowsiness
![3](https://user-images.githubusercontent.com/105065454/170831835-64757af2-d9a5-404d-a26e-e64c157dba3a.jpeg)

## output at high drowsiness
![1](https://user-images.githubusercontent.com/105065454/170831847-139e2f5c-e0e8-4ad0-bf15-586899e3b939.jpeg)

### Drowsiness Detection using python

run using script:

- `python project.py`
- `python model.py`

### Drowsiness Detection using python3

run using script:

- `python3 project.py`
- `python3 model.py`
### Files required
  
     models
     - cnnCat2.h5
     haar cascade files
     - haarcascade_frontalface_alt
     - haarcascade_lefteye_2splits
     - haarcascade_righteye_2splits
     alarm.wav
  
