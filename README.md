# smarthome
Main components used : esp32 camera modeule, PIR motion sensor, Relay board

## Control room lights using a telegram bot.
The room lights are connected to the esp module through a relay board, and can be controlled from anywhere through the telegram bot.

## Intruder Alert Mode
If the intruder alert mode is activated, the bot notifies you and sends a picture of the room every 5 seconds.

## Energy Conservation Mode
If no motion is detected for 1 minute, the lights and fans are automatically turned off to conserve electricity.
Whenever someone enters the room, they toggle back on.
