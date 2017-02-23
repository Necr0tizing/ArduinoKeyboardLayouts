# ArduinoKeyboardLayouts
Arduino keyboard languages for easy swapping of keyboard layout codes to match your language, ideal for non US users

1. Go to your Arduino Library usually located in "C:\Program Files (x86)\Arduino\libraries\Keyboard\src".

2. Make a backup of your "Keyboard.cpp" and save it somewhere safe.

3. Copy the Keyboard.cpp in your chosen keyboard language, from this repository to "C:\Program Files (x86)\Arduino\libraries\Keyboard\src".

4. Voila it should now work so every time you use the #include "Keyboard.h" you will now be able to write directly in your language.
