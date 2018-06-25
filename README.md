# IOT-PROJECT
## Using raspberry pi and other things to create a final project
### Introduction:
#### (1)
We need a "Temperature and humidity sensors" to get something we need,and the sensor I bought is a DHT22+PI sensor.
The image is how we should do on breadboard.
![image](https://github.com/gary31136/IOT-PROJECT/blob/master/dht22.PNG?raw=true)<br>
And this tutorial will guide you steps to setup the dht22 sensor:<br>
1. `git clone https://github.com/adafruit/Adafruit_Python_DHT.git`<br>
2. `cd Adafruit_Python_DHT`<br>
3. `sudo apt-get update`<br>
4. `sudo apt-get install build-essential python-dev`<br>
5. `sudo python setup.py install`<br>
6. `cd examples`<br>
7. `sudo ./AdafruitDHT.py 2302 4`<br>
![image](https://github.com/gary31136/IOT-PROJECT/blob/master/dht22%20run.PNG?raw=true)<br>
#### (2)
We need two seven-segment displays to show digit in ones and digit in tens.<br>
The image is how we should do on breadboard.
![image](https://github.com/gary31136/IOT-PROJECT/blob/master/seven%20segment.PNG?raw=true)<br>
And the code is in the file "seven-segments"<br>
But the code is only for example,not the real code using on raspberry pi.<br>
#### (3)
The last,we will need Raspberry Pi Camera Module<br>
and we have to Connect the Camera Module<br>
![image](https://github.com/gary31136/IOT-PROJECT/blob/master/picamera.PNG?raw=true)<br>
Then open the Raspberry Pi Configuration Tool from the main menu:<br>
and ensure the camera software is enabled:<br>
![image](https://github.com/gary31136/IOT-PROJECT/blob/master/picameraenable.PNG?raw=true)<br>
Then Open Python 3 from the main menu<br>
and open a new file and save it as `camera.py`<br>
the `camera.py`'s code is in the file "camera.pyfile",and the code will let your picamera takes a picture for you after 10 seconds you press f5.<br>
The most important thing is "tensorflow"
And this tutorial will guide you steps to setup the tensorflow:<br>
1. `conda create -n project python=3.5.2`
2. `source activate project`
3. `pip install numpy`
4. `wget https://github.com/lhelontra/tensorflow-on-arm/releases/download/v1.8.0/tensorflow-1.8.0-cp35-none-linux_armv7l.whl`
5. `pip install tensorflow-1.8.0-cp35-none-linux_armv7l.whl`
6. `git clone https://github.com/tensorflow/models.git`
7. `cd ~/tensorflow/models/tutorials/image/imagenet`
8. `python classify_image.py --image_file ~/pictures/A.jpg`<br><br>
### Video demo
[Video Demo](https://youtu.be/pNEht-3bFzw)
