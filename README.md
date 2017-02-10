# Introduction

Support for setting up an environment for using Arduino with makefiles while using the Arduino-rp6-library.

## Used projects

+ [Arduino-Makefile](https://github.com/sudar/Arduino-Makefile)
+ [arduino-rp6-library](https://github.com/b3nzchr3ur/arduino-rp6-library)
+ [Cutecom](http://cutecom.sourceforge.net/): graphical application for serial port communication

## Tested systems

+ Linux

## Installation

Run the following commands in a terminal:

```
wget https://raw.githubusercontent.com/b3nzchr3ur/arduino-rp6-make-install/master/arduino-rp6.install
bash arduino-rp6.install
```

## Building and uploading projects

Check out the [examples](examples) directory for some example projects.

Building one of the example projects:

+ Open a terminal
+ Navigate to the project directory (f.i. [examples/rp6-master](examples/rp6-master))
+ Build the project with terminal command: `make`
+ Check if the com-port definition of your Arduino in the Makefile (f.i [examples/rp6-master/Makefile](examples/rp6-master/Makefile))
+ Upload the project to your Arduino board: `make upload`

More information available on: [Arduino-Makefile](https://github.com/sudar/Arduino-Makefile). 



