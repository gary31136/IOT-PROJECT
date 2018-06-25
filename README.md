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
