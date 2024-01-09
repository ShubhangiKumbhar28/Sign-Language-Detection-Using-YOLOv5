# Sign-Language-Detection-Using-YOLOv5

This project developed using YOLOv5 and aims to detect sign language gestures .
I collected sign language images, annotated them with labelImg, and trained a model. Download the best.pt model to experience  sign language detection. Use the provided script (python run.py) for live camera testing and test the model's ability to identify specific sign language classes ('Hello','Yes','No','Thanks','Sorry','IloveYou','Please').

 

Follow the steps below to set up and run the project.

Step 1: Capture Images

Run the following command to capture images using the provided code

```
python images_capture.py
```

Step 2: Label/Annotate Images

Install labelImg using the following command:

```
pip install labelImg
```
Label/Anotation Images to get co-ordinates of required part of the data and save in labels folder
```

labelImg
```

Step 3: Clone YOLOv5 Repository

```
!git clone https://github.com/ultralytics/yolov5.git 
```

Step 4: Install Requirements

```
pip install -r requirements.txt
```

Step 5: Live Detection

To perform live detection on classes the model has been trained on.

```
python run.py
```

# Sign Language Detection Using YOLOv5


```

![No](images/sign_language_gesture.png)

```






