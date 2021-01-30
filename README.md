# face-recognition

Setup
=========
brew update  
brew install cmake  
pip install -r requirements.txt

Usage
================
encoding: python encode_faces.py --dataset <path_to_dataset> --encodings encodings.pickle  
recognize image: python src/recognize_faces_image.py --encodings encodings.pickle --image <path_to_test_image> --detection-method hog  
recognize video: python src/recognize_faces_video.py --encodings encodings.pickle --output output/webcam_face_recognition_output.avi --display 1 --detection-method hog  



A Sub-Section
-------------

<here is a subsection>
Numbered list:
1. hello
2. goodbye

