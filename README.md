## Emergency Alert System
A project designed, written, and built by [Jacob Ellington](https://www.github.com/cannotilever)

This github account contains the Block 2 (latest) version of the HVRHS Emergency Alert System, designed to run on the raspberry pi platform as an inexpensive and more configurable alternative to commercial public alert systems. The system conststs of raspberry-pi powered button stations spread throughout the school, raspberry-pi driven strobes, a webserver for administration, a coordination program, and desktop software to display alerts when an emergency condition is active.

Currently, only 3 of the components' repositories are public as the rest of the system is still undergoing testing, and may not be representative of the final product.

Please note: this system was designed to run on its own subnet, logically separated from any non-privilidged systems and as such, potential security vulnerabilities such as DNS poisoning or the interception of clear-text communications were not deemed a priority.

### Concept Diagrams
Please note that these diagrams were created during the concepting phase before I ever learned Rust and do not reflect how the systems acutally work in their current state, rather they provide a general overview of the project's goals.

![System Coordination Software](https://github.com/EAS-block2/EAS-block2/blob/main/Ops%20Server.svg)
![Pi Strobe software](https://github.com/EAS-block2/EAS-block2/blob/main/Pi%20Endpoint.svg)
![Button Computer software](https://github.com/EAS-block2/EAS-block2/blob/main/alarm%20from%20button.svg)
