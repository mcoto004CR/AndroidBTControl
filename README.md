# AndroidBTControl
Android App that connects android phone to raspberry Pi using Bluetooth

This application will connect you Android device (any OS) to a Raspberry Pi3 via bluetooth, so you can use it as a terminal to send and receive commands/text, a free python script is provided so you can customized commands and instructions. You can also use voice commands using Google voice to text feature.

There are some simple steps you need to follow on your Pi3 to get started.

1.- You will need to install Blue manager in the Pi3: sudo apt-get install bluetooth bluez blueman

2.- Pair you mobile device and the Pi3 using Blue prior test the app.

3.- Run a terminal window on the Pi and get your MAC address: sudo hciconfig.

4.- Then download and extract to your Pi the following Python scrip at: www.crhostservices.com/btpython/btpi3_receiver.rar

5.- Execute the script from the folder you saved it: sudo python btpi3_receiver.py

6.- Now go back to the app main screen and select your Pi3 mac address, you should be connected shortly to the Pi.

7.- Enter data to send to the Pi3 either by typing or using voice commands, once sent you will get the same data replied from the pi. Type/Say 'exit to stop the connection. \n\n

You can read the same set of instructions within the app, just click the instructions button.

Feel free to modify the python script as required, enjoy Marco C.
