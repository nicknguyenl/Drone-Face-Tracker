# Drone-Face-Tracker

Installation Requirements:
* Python == 3.7
* numpy == 1.21.6
* opencv == 4.5.5.64
* djitellopy == 2.4.0

How to Use:
1. Connect to DJI Tello Drone's Internet
2. Run command in terminal: 'python main.py --model_file res10_300x300_ssd_iter_140000_fp16.caffemodel --proto_file deploy.prototxt.txt'
3. Drone will automatically launch and a video stream will be displayed in a separate window
4. Get in the drone's camera view and it will then detect and track your face 
