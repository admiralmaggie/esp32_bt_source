ESP32 Bluetooth A2DP-SOURCE 
========================

## Summary
This ESP32 demo is based on ESP-IDF A2DP-SOURCE code. The demo is modified so sink is sourced with music (instead of static) which is stored in music.h header (16bit/44100 sample rate). The demo's connect/disconnect looping mode is disabled. You can specify a BT MAC to skip pairing/discovery mode. The partion table is modified to allow for storage of music.h file.

## BT Security Database
To delete ALL existing BT paired devices, push RESET button and then immediate hold down BOOT button (do not hold down BOOT while pressing RESET! that would place the device in download mode.)
  
