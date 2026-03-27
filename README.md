
## ESPHome

### Elecrow CrowPanel Advance 7.0-HMI ESP32 AI Display


![Image of the Elecrow CrowPanel Advance showing the ESPHome logo.](Images/elecrow-crowpanel-7-hmi-ai-home.jpg)

"This is a voice assistant project that ports the ESP32-S3-BOX-3 ready-made project to the Elecrow CrowPaneL Advance 7.0-HMI ESP32 AI Display. It has full wake word and voice functionality. The long-term goal is complete feature parity with the ESP32-S3-BOX-3 project. It also sends a esphome.tts_uri event to Home Assistant with the URL for the audio response, thanks to the work done by [@formatBCE](https://github.com/formatBCE). This assistant is currently a work in progress, and has been [documented on XDA](https://www.xda-developers.com/built-google-home-hub-replacement-esp32-display/). It requires the S1 and S0 switches to be set to 0, so that both MIC and SPK are enabled. 

There are a number of improvements necessary to make this particular project more user-friendly, such as adding display brightness control."

#####
I have modified the code for the Elecrow CrowPanel Advance 7.0 v1.2.
Fixed an audio issue where responses could not be heard.
Added backlight brightness control.
Increased the PSRAM speed to 120Mhz.
But still improvements are needed,no text responses on the display.....
Added yaml to voice assistant and control panel (https://github.com/strange-v/RemoteWebViewClient)
