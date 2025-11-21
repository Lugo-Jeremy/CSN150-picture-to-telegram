# CSN150-picture-to-telegram
JEREMY LUGO  

NOTES FOR CSN150

Purpose:

To send and recieve messages on Telegram via a bot created by me using the ESP32 CAM through Arduino IDE

Equipment Used:

ESP32 CAM, USB-C Cable

Tools used: 

Arduino IDE, Telegram Mobile App

Steps I Followed:

1.Create an account on Telegram (download Telegram app)


2.Look up BotFather on Telegram and create a bot


3.Save bot token that is given to interact with the bot (used for code later)


4.Look up IDBot on Telegram to get user ID number (used for code later)


5.Open Arduino IDE and plug in ESP32 CAM


6.Download ZIP-File "Universal Arduino Telegram Bot library" from https://randomnerdtutorials.com/telegram-esp32-cam-photo-arduino/


7.In Arduino, Go to Sketch > Include Library > Add.ZIP Library to add the library downloaded


8.Install ArduinoJson Library by going to Sketch > Include Library > Manage Libraries and searching "ArduinoJson"


9.Copy code for the Telegram bot given from https://randomnerdtutorials.com/telegram-esp32-cam-photo-arduino/, update network credentials along with telegram bot token and user ID and upload


10.After upload is successful, press RST button on ESP32 CAM to make sure there is a response on the Serial Monitor in Arduino


11.Search up bot that you created on Telegram (my bot's name is Ximmer_bot)


12.Start conversation with bot to intialize the response (/start)


13.Have the bot flash LED light (/flash), type /flash again to turn LED off


14.Send /photo to take a photo from ESP32 CAM (do to command more than once to get a clear image sent to the bot)


 
Final Report:

Telegram bot was a success. I was able to create a bot using the Telegram app and successfully being able to interact with it using the ESP32 CAM setup through Arduino IDE. The code was successful, no issues were encountered. Upload was smooth, Telegram was able to successfully respond to my commands. Whole process went smoothly, no issues encountered.
