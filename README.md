# apama_GPIO
A C++ based EPL Plugin for interfacing [Apama](http://www.apamacommunity.com/) with the GPIO system on the RaspberryPi.

currently only the gpio plugin is functional - and only if you have wiringpi installed which is no longer prepackaged with Raspberry Pi OS.
To get wiringpi (working Dec 2021):
```
cd /tmp
wget https://project-downloads.drogon.net/wiringpi-latest.deb
sudo dpkg -i wiringpi-latest.deb
```
new todos:
* Update lib to use pigpio instead of wiringpi
* Morse code should support numbers
* Should be able to play Morse on multiple pins without blocking

key todos (old, needs investigation)
* integrate xpybuild
* further investigation and development of SPI plugin (potential to be merged into GPIO plugin)
* attach https://github.com/markhorsburgh/cpp-sense-hat as a submodule
