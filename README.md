# emotion-detection-knn
Emotion detection using KNN and OpenCV
Open Google Colab and create a new notebook.
Upload emotion_detection.py.
Upload the dataset zip file.
Unzip the dataset so the folder structure is:
/content/train/
  angry/
  disgust/
  fear/
  happy/
  neutral/
  sad/
  surprise/

/content/test/
  angry/
  disgust/
  fear/
  happy/
  neutral/
  sad/
  surprise/
  
Run the folllowing command:
!python /content/emotion_detection.py

The script will:

Train the KNN model

Display evaluation plots and metrics

(Optional) Start real-time emotion detection using webcam
