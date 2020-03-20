# DHT11-Flask
Display Temperature and Humidity on Flask Web page

See ```https://github.com/BEUTControls/DHT11``` for setting up and using flask.

navigate to your folder of choice on the raspberry pi.

create a new file ```sudo nano dht11flask.py``` copy the contents from dht11flask.py from this site and paste to your ssh session. You can paste into ssh session by Right clicking in the session.

create a new subfolder in the same directory that you saved the dht11flask.py.

```sudo mkdir templates```

Change to the templates directory

```cd templates```

Create a new file.

```sudo nano index.html```

Copy the contents from index.html and paste into ssh by right clicking in the session.

Now start dht11flask.py

```sudo python dht11flask.py```

Navigate to IE of Chrome and type.

```http:\\YOUR_RPI_IP_ADDRESS:8008```

You should now see a nicely formatted temperature and humidity display.

Next project will be to get multiple Rpi/DHT sensors to read on a single webpage.
