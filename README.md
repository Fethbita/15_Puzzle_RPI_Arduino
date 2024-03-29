# 15 Puzzle Game implementation for Raspberry PI and Arduino

15 Puzzle game implemented using C for Raspberry PI Model B+ and then later ported to Arduino.

## Demonstration

The following is a recording of the normal difficulty gameplay emulated using [Wokwi](https://wokwi.com/):

![15 Puzzle Normal Difficulty Gameplay](/15puzzle_normal_gameplay.gif "15 Puzzle Normal Difficulty Gameplay")

## Requirements

* Raspberry PI or Arduino
* 20x4 LCD
* 250kΩ potentiometer
* 4 push buttons
* 4 10kΩ resistors

## Raspberry PI Model B+

Raspberry PI version requires the deprecated [wiringPi](http://wiringpi.com/) library. It can be installed from the [unofficial wiringPi mirror](https://github.com/WiringPi/WiringPi).

[Fritzing](https://fritzing.org/) Breadboard Model of Raspberry PI Model B+ (what I originally implemented for)

![Raspberry PI Fritzing Model](/15puzzle_rpi_bb.png "Raspberry PI Fritzing Breadboard Model")

## Arduino Nano

[Fritzing](https://fritzing.org/) Breadboard Model of Arduino Nano

![Arduino Nano Fritzing Model](/15puzzle_arduino_bb.png "Arduino Nano Fritzing Breadboard Model")
