# Retevis RT622P

> FRS version is the same hardware-wise RT22P.

Out of the box the radio is programmed with PMR446 frequencies and classic Retevis subtone selection. 
They will work with eachother, but to talk to other radios, you may need to set up the subtones the same on all of the used equipment.

# Buttons
- Volume knob + power
- Up
  - Short press: Channel up
  - Long press: Monitor
- Down
  - Short press: Channel down
  - Long press: Scan (Voice prompt for On/Off)
- Menu button
  - Short press: ?
  - Long press: Lock (one beep = Locked, two beeps = Unlocked)

# Programming

Software can be found in the repo.
Programming cable: [SKU J9138P](https://www.retevis.com/rt20-rt65-rb19-usb-programming-cable-eu).

The cable is plug and play on Windows 10. Just select the corresponding COM port in the CPS.

# Unlocking

> It is illegal to use higher power that 0.5W on PMR446 frequencies. Use this only if you want to use the radio on other frequencies you are licensed to use (HAM).

Unlock code `retevis` will open up changing frequencies and power output settings. On "Hight" (spelled as in CPS - code plug software) should be up to 3W.

![RT622p](/Retevis%20RT622P/Retevis-RT622p.jpg)
