# cuoredinapoligram
pulse a led when match the hashtag


liberamente tratto da

https://github.com/weblancaster/instagram-real-time

e modificato con
https://www.npmjs.com/package/rpi-gpio

clonare tutto nella cartella con git clone 
poi
npm install

e per sicurezza dopo

npm install rpi-gpio

installare anche

https://github.com/quick2wire/quick2wire-gpio-admin

con un git clone e poi

cambiare

sys/devices/virtual/gpio/ in /sys/class/gpio/

all'interno di quick2wire-gpio-admin/src/gpio-admin.c

poi

$cd quick2wire-gpio-admin
$make
$sudo make install
$sudo adduser $USER gpio
 
uscire e rientrare dal terminale
