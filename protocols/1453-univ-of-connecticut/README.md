# PicoGreen Quantification for 96 Samples

### Author
[Opentrons](http://www.opentrons.com/)

## Categories
* Molecular Biology
    * DNA

## Description
This protocol allows your robot to perform DNA quantification using Quant-iT™ PicoGreen® on 96 samples, using a P300 multi-channel and a P10 multi-channel pipette. You will need two [black 96-well quantification plates](http://www.eandkscientific.com/96-Well-Microplates-Flat-Bottom-Medium-Binding-Surface-Black.html), a 96-well sample plate, and a [12-row trough](https://www.usascientific.com/12-channel-automation-reservoir.aspx).

### Robot
* [OT-2](https://opentrons.com/ot-2)

### Modules

### Reagents
* [Quant-iT™ PicoGreen™ dsDNA Assay Kit](https://www.thermofisher.com/order/catalog/product/P7589)

## Process
1. Download your protocol.
2. Upload your protocol into the [OT App](https://opentrons.com/ot-app).
3. Set up your deck according to the deck map.
4. Calibrate your labware, tiprack and pipette using the OT App. For calibration tips, check out our [support article](https://support.opentrons.com/ot-2/getting-started-software-setup/deck-calibration).
5. Hit "Run".
6. Robot will transfer 100 uL of TE buffer to column 1 (well A1, C1-H1) of both black assay plates.
7. Robot will transfer 150 uL of DNA standard to well B1, then perform serial dilution of 50 uL down column 1 of both plates.
8. Robot will distribute 99 uL of TE buffer to column 2-7 of both plates.
9. Robot will transfer 1 uL of sample from the first half of the sample plate (column 1-6) to black assay plate 1.
10. Robot will transfer 2 uL of sample from the second half of the sample plate (column 7-12) to black asasy plate 2.
11. Robot will distribute 100 uL of PicoGreen ssDNA reagent to all of the occupied wells.

### Additional Notes
Tip Rack Setup
* Remove the second tip from column 1 of the 300 uL tip rack in slot 7.
---
Trough Setup
* TE Buffer: well A1
* PicoGreen ssDNA Reagent: well A2
---
Tube Rack Setup
* DNA Standard: well A1
---
Before you run this protcol, make sure to take a look at the [Application Note](https://www.promega.com/-/media/files/products-and-services/instruments/detection/tbs-technical-support-docs/997-9314.pdf?la=en) for the Quant-iT PicoGreen dsDNA Kit to ensure you have all the correct materials needed for your experiment.

If you have any questions about this protocol, please contact protocols@opentrons.com.

###### Internal
daHmpE0h
1453
