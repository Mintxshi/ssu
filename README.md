# ssu
sms start up

---------------------------
## required

node (16 or higher)

crontab

UNIX based file system

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

---------------------------

## how 2 run at bootup

1. open a terminal
2. execute `touch ~/ssu.sh`
3. copy ssu.sh into ur ssu.sh file
4. execute `crontab -e`
5. at the bottom of the file write
```
@reboot sudo /home/pi/ssu.sh
```
6. complete.
