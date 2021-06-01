#### Tweaked Markus' firmware for the 'Blue Button' LCR-T4 model from techtonics.in.

The images in this repository are borrowed from the internet for reference purposes.

Current repository version is ComponentTester-1.43m.tgz. Only `Makefile` and `config_328.h` are tweaked.

Usage:

```
sudo apt install avrdude avr-libc binutils-avr gcc-avr git  # once

cd ComponentTester-1.43m

make upload  # use usbasp programmer!
```

URLs:

- https://github.com/Mikrocontroller-net/transistortester/tree/master/Software/Markus (upstream)

- https://www.thingiverse.com/thing:2890162
