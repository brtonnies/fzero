# Welcome to Dev!

## File Structure
/dev
|--scripts
|--protocols
|--|--<protocol-name>
|--|--|--README
|--|--|--apps
      |--payloads
| README

### Scripts
Collection of helper and utility scripts for various purposes.

### Protocols
+ Bluetooh
+ GPIO
+ Infrared
+ NFC
+ RFID
+ Sub-GHz
+ USB
+ WiFi 
+ (Media, Games, and Tools are included here as well).

#### Applications (apps)
+ Applications are exactly that, organized here by protocol.  
+ For publication, they need to be accessible as a public repository (but who says we're publishing them?), which we can probably write a script to handle.

#### Payloads
+ These are written for a protocol, typically utilized within an application  (think saved IR remotes/NFC tags/bad-KB attack files/etc.)
+ This is where (I believe) RubberDucky scripting will be useful for writing custom versions of the aforementioned files rather than using direct reads/writes or copies of other payload files.
+ Unlike applications, these should be able to be dropped right into their respective protocol folder on a flipper device (Flipper Lab, etc.) and then be usable right away -- one exception being if they're developed for a custom application.

### Notes
+ This file structure may not be ideal, but it will work while we're figuring things out.

## Resources
+ Application Development Tutorial(s)
  + [Instantiator's Tutorial Series](https://instantiator.dev/post/flipper-zero-app-tutorial-01/)