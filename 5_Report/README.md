
## Introduction

Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed
and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear
window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper
arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called
pressure points or claws that are small arms under the wiper


## SOFTWARE REQUIREMENTS

STM32 CUBE IDE

## COMPONENTS

STM32F4O7VG MICROCONTROLLER BOARD

## Description

Using the high-performance STM32F407 microcontrollers' capabilities, the STM32F407 Kit makes it simple for customers to build audio-based applications. A digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector are all included. Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are powered by the Arm® Cortex®-M4 32-bit RISC processor, which runs at up to 168 MHz.

## Working principle 

Assume that the microcontroller is the car. When you click the button, the first led (red) illuminates, the wiper activates, and the second led (blue) illuminates at the right rate. If the button is pressed again, the third led (green) will illuminate, and the wiper speed will be increased, in contrast to the previous one. The fourth press will turn on the fourth led (orange) and increase the wiper speed in the same manner as the previous one. The microcontroller (vehicle) is turned off after the fifth click.

## Working

The working of the wiper is based on the conversion of the wiper
motors linear motion into linear back and forth movement of the
wiper blades. The wiper combines two mechanical technologies
to perform their tasks:
A combination of electric motor and worm gear reduction power
to the wipers and a neat linkage converts the rotational output of
the motor into the back and forth motion of the wiper.
Motor takes a lot of force to accelerate the wiper blades back and
forth across the windshield so quickly. In order to generate this
type of force, a worm gear is used on the output of a small
electric motor. The worm gear reduction can multiply the torque
of the motor by about 50 times and can slow it down with the
same force. The output of the gear reduction operates a linkage
that moves the wipers back and forth. Inside the motor/gear
assembly is the electronic circuit which senses the wipers are in
their down position. The circuit maintains power to the wipers
until they are parked at bottom of the windshield, and then cuts
the power to the motor. A short cam is attached to the output
shaft of the gear reduction. This cam spins around as the wiper
motor turns. The cam is connected to a long road; as the cam
spins, it moves the rod back and forth. The long rod is connected
to a short rod that actuates the wiper blade on the driver’s side.
Another long rod transmits the force from the driver’s side to the
passenger’s side wiper blade.

## Applications

* Car
* Truck,Bus

## Who

 For common people 

## What 

Car wiper control system

## When

At the time of raining

## How 

By using STM32


## Engine on state
![168213634-987e1673-4798-49e1-85fb-ef7bb3d9278d](https://user-images.githubusercontent.com/88073170/168268099-ffdd325b-b247-49a0-9deb-2bbd9c1db598.png)

## Low speed

![168213634-987e1673-4798-49e1-85fb-ef7bb3d9278d](https://user-images.githubusercontent.com/88073170/168268099-ffdd325b-b247-49a0-9deb-2bbd9c1db598.png)

## Moderate speed

![168213634-987e1673-4798-49e1-85fb-ef7bb3d9278d](https://user-images.githubusercontent.com/88073170/168268099-ffdd325b-b247-49a0-9deb-2bbd9c1db598.png)

## High speed

![168213634-987e1673-4798-49e1-85fb-ef7bb3d9278d](https://user-images.githubusercontent.com/88073170/168268099-ffdd325b-b247-49a0-9deb-2bbd9c1db598.png)

## Engine off state

![168213634-987e1673-4798-49e1-85fb-ef7bb3d9278d](https://user-images.githubusercontent.com/88073170/168268099-ffdd325b-b247-49a0-9deb-2bbd9c1db598.png)
