# April 10th class meeting notes

volatile: compiler that gets used inside of an interrupt function.
generally you don't really use volatiles and interrupts, kind of complex?

analog oscilloscope - time by voltage, shows voltage over time.
logic analyzer.

ATTiny85
Sparkfun - avrisp > programmer for usb $20.
atmel ice does a lot more it's expensive though.

All do the saem thing:
++ = +1
brightness = brightness + 1
brightness =+ 1

can "source" current - arduino to gnd. can source ~ 20mA per pin on arduino.
"sync" current - arduino to power

what can go wrong w a relay?
a circuit that caused the relay to oscillate.
relays have a certain number of clicks it can do.
high current: the switch cause cause a stroke of lightning and can solder itself together.

solid state relay: relay with no moving parts

serial.write > sends a byte. we've been using serial.print

## April 12th

We went over ordering products again on Mpuser and DigiKey, it's pretty difficult.
Amazon and google aren't going to always give you what you need.

Reed switches, very simple STSP magnet switches.

OshPark > really nice circuit boards.
JLCPCB > if you want a lot or if you want parts soldered on. circuit boards.

Motor:
3 Non polarized capacitors to smooth out the power.

12V power supply. AC.
Wallwort > 12V.

7805 - voltage regulator part #. turns higher voltage (max 15V?) into 5V.
