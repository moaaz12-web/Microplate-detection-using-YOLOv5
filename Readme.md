# Guidance file

1. The .ipynb file contains the full code for training the model and testing it, and also exporting it as well. You do not need to run it anymore since we have already trained the model.

2. The yolov5 folder contains the full yolo model dependencies. Inside it, there is a 'runs' folder which contains all training and evaluation metrics for the model.

3. Inside the 'yolov5/runs/train/weights, we have best-fp16.tflite model. It is the yolo model weights exported in tflite format which you can use in your Android studio.

4. You do not have to run the .ipynb file, it is just for proof of training. If you want to run it again, you would have to first download the dataset from this link "https://drive.google.com/drive/folders/18U0gQetGk9y2s-UF7RaHBKSA-EdTk3Zr?usp=drive_link", then place it over here, and then change some paths in the code file as well.

5. The report.doc file contains the report for the model training and evaluation.