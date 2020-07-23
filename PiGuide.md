Raspberry Pi TLDR guide

WTF IS THIS?
	this document exists to help people making the light navigate the hardware component specifications. a "raspberry pi" is a cheap generic all-in-one computer that costs approximately $40, runs on USB power, and uses smaller lower-power chips like the ARM core processors to do classical computer work instead of merely phone operations.  WHY SHOULD YOU CARE? because for $40 bucks ish, you suddenly have a component that can automate the rest of the hardware, that you can reasonably control from your phone, even remotely over the internet.

WHAT DO I NEED TO KNOW?
	the Pi runs on USB power
	It uses standard USB interfaces for things like keyboards and mice
	it uses standard HDMI for video but it can also accomodate a touchscreen or send AV signal out to an older television
	You need to know how to "flash an image" to an SD card, using a program such as "Etcher" to make the SD card "look like a system" to a computer 'reading' it.  With this information, you need to then flash an image of "Raspbian" (or perhaps some other suitable OS with the correct hardware drivers for this, such as many versions of linux and even an IOT version of Windows) to your micro SD card, and then you have to put it in the Pi ('as the hard drive').
	most pis have wifi on them (but some don't, you should double check to make sure if you buy a pi0)
	the older pi's have a higher-than-standard current draw and thus need a higher-amperage (but still 5 volt) power supply. This is a consideration if you are buying anything previous to the pi4, which uses standard usb-c at standard power ratings.
	
WHAT DOES THE PI DO THAT I NEED?
	-automation.  automatically control your lights, control stuff from your phone, etc.
	-networking. know about your plants at any time, even remotely.
	-data collection. Keep a log of your data points and be able to objectively compare them in order to tune your plant interventions.
	-sensor expansion. Add an infinite variety of new sensors; since the pi runs all standard computer interfacing hardware, any digital sensor that you can buy for a computer can be used with it, and because of the GPIO ports on the pis, not only can literally any sensor of any type with a digital voltage change be wired up to the pi by an informed user, but there is the potential to create new categories of sensors yet to be conceived of and be able to wire these in to the pi also.
		-this sensor thing really needs to be rammed home, so a short list includes radar, sonar, laser, microphone with microdecibel accuracy, PH, conductivity, magnetism, all sorts of neat fluid measuring flow rate sensors for plumbing, all sorts of current measuring stuff for electric, all sorts of thermisters for temperature tracking and piezoelectric sensors that can measure the barometric pressure in the air as easily as they can be used to record sounds.
