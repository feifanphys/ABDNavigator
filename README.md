# ABDNavigator (Atom-Based Device Navigator)
Scanning probe control and sample navigation for atom-based devices.

## Project Components:
**ABDNavigator** is the primary interface seen by the end-user.  It is meant to be user friendly with a google-maps-like interface in which elements of the "map" such as scanning probe images, optical images, lithographic designs, and labels are editable and can be overlayed and aligned with one another.

**ABDController** is designed to interface with a scanned probe controller, providing a means for the ABDNavigator to communicate with and control a scanning probe.  Currently an interface to the ScientaOmicron Matrix controller is implemented, though by design ABDController can be extended in a modular fashion to implement communication with other scanning probe controllers that provide sufficient APIs.  

## Contents:
1. Installation
1. Usage (how to run ABDNavigator)
1. Contributing
1. License
1. How to cite

## 1. Installation:
The two project components, ABDNavigator and ABDController, are provided as source and can be installed by compiling following the instructions in [ABDNavigator/INSTALL.md](https://github.com/usnistgov/ABDNavigator/blob/master/ABDNavigator/INSTALL.md) and [ABDController/INSTALL.md](https://github.com/usnistgov/ABDNavigator/blob/master/ABDController/INSTALL.md), respectively.

## 2. Usage (how to run ABDNavigator):
[ABDNavigator/run.bat](https://github.com/usnistgov/ABDNavigator/blob/master/ABDNavigator/run.bat)

[ABDController/ABDController.bat](https://github.com/usnistgov/ABDNavigator/blob/master/ABDController/ABDController.bat)

## 3. Contributing:

## 4. License:
See [LICENSE.md](https://github.com/usnistgov/ABDNavigator/blob/master/LICENSE.md).

## 5. How to cite:
DOI comming soon.
