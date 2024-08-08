# rp2040-motor-controller
A dual channel brushless motor controller based on the RP2040 microcontroller

The boards cost between $15 and $40 each depending on version and quantity.

![A photo of the new modular design.](docs/R3_complete.jpg)
![A photo of the new modular design, disassembled.](docs/R3_parts.jpg)
![A photo of the new modular design with a motor.](docs/R3_motor.jpg)

```
NOTE: This design is still changing. There is currently one board version in
this repo. This is our dual CPU version with CAN bus and extra connectors for
our robot. This version also improves the current measurement circuit compared
to the first rev.

Once we have verified the improved current measurement circuit, we will also
support a single CPU version which is smaller and slightly cheaper. This will
look similar to our first prototype version shown in the top of the photo at the
bottom of this document. To view the files for that board see this commit:
https://github.com/Twisted-Fields/rp2040-motor-controller/commit/ceeeb0ee0d24856a9ad8b6b036be5baf15e3ead6
```

> **Warning**
> These files are still under development and undergoing testing. While we do
> aspire to produce a design that others can easily fabricate, we do not yet
> recommend making them for yourself! Please post questions on board status
> to our community forum at [community.twistedfields.com](https://community.twistedfields.com).

Our dream is that you will fab your own boards, make changes, and share your work - giving this design life beyond our efforts.

Designed by Taylor Alexander for Twisted Fields, for the Acorn Precision Farming Rover.

Many thanks to [Daniel Theobald](https://www.twistedfields.com/blog). Without your financial support and encouragement this project would not have been possible.

Thanks to all of our supporters on Open Collective. Your contributions are helping grow this project in to a sustainable open source organization.

You can support this project yourself at our [Open Collective Page](https://opencollective.com/twisted-fields-research-collective).
(UPDATE: Our fiscal host on Open Collective has closed. We are seeking a new host.)

To learn more about Acorn, please see our [announcement blog post](https://community.twistedfields.com/t/introducing-acorn-a-precision-farming-rover-from-twisted-fields/).
Or see a more recent [technical update here](https://community.twistedfields.com/t/march-2022-update-simulation-brakes-funding-and-navigation-improvements/202).

![A photo of both PCB designs](docs/dual.jpg)
