# Facial-Expression-Recognition
**Use it on Default**
- Install all the requirements: `pip3 install -r requirements.txt` <br>
- Now run the main.py: `python3 main.py` <br>
- Go to your browser and open localhost: `0.0.0.0:5000` <br>

**To use it on Webcam or any other video**
- Go to **camera.py**. <br>
- Look for `class VideoCamera(object)` <br>
- Now remove the directory in `cv2.VideoCapture()` function and add **0** as an integer argument for **Webcam** or just
change the directory for other videos. <br>
- Now run the main.py: `python3 main.py` <br>
- Go to your browser and open localhost: `0.0.0.0:5000` <br> 
