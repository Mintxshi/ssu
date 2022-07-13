# ssu
sms start up

---------------------------
## **THIS REQUIRES A TWILIO ACCOUNT WITH SMS. WITHOUT IT, IT WILL NOT WORK.**
---------------------------
# how 2 install

1. clone the thing into ur desktop **( /home/pi/Desktop/ssu )**
2. execute commands in order

`npm i twilio`

`npm i dotenv`

`npm i axios`

`npm i math.js`

`npm install`

3. go into the `.env` file, there are instructions there.
4. open a terminal
5. execute `sudo nano /etc/xdg/autostart/ssu.desktop`
6. paste the following
```
[ssu Entry]
Name=ssu
Exec=/usr/bin/node /home/pi/ssu/index.js
```
7. u should be done  :)
