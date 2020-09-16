# Face recognition project

The project is wirtten by pure python. 
To use text the project, you have two choices.
First extract the face data zip file.
Second make sure install python libiary face_recognition and opencv-python onto your device.
To install face_recognition: run `pip install face_recognition`
To install opencv-python: run `pip install opencv-python`
Then, connect your device with a webcam or connect with a smartphone(see tutorials below)and run the program.
To use smartphone, install https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en on your phone
modify `capture = cv2.VideoCapture(video)` to `capture = cv2.VideoCapture(http://admin:admin@address_that_app_provide)`
