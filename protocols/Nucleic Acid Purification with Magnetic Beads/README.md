# Nucleic Acid Purification with Magnetic Beads

### Author
[Opentrons](https://opentrons.com/)

## Categories
* Molecular Biology
    * Nucleic Acid Purification

## Description
With this protocol, you can perform high-quality nucleic acid purifcations using magnetic beads and the [Opentrons Magnetic Module](https://shop.opentrons.com/products/magdeck?_ga=2.120183432.1039841802.1542049668-403439593.1535387376). With this setup, you can get high quality PCR product and other nucleic acids without the use of centrifugation or vacuum separation. Here is our [Technical Note](INSERT LINK).

---

---

***Example Setup***

- Pipette and Mount : Specify the pipette and mount, left or right, for your protocol. We recommend the p50 and p300 single or multi-channel pipettes for the volumes of reagents in this experiment. 
- Sample number: Users can customize the number of samples to run per protocol. We recommend multiples of 8 if you are using a multi-channel pipette. 
- Sample volume: The starting volume of the input sample can be customized. We recommend volumes about 10 µL. 
- Bead Ratio: The ratio of beads can be customized for left or right side size-selection of fragments. The default bead ratio is 1.8x the input sample volume. 
- Elution Volume: Users can choose the final volume to elute the purified nucleic acid. The Opentrons MagDeck supports elution volumes above 10 µL. 

**Advanced Parameters**
- Incubation Time: The incubation time is the amount of time that the bead solution and input sample interact. The default incubation time is 5 minutes.
- Settling Time: This parameter allows the beads to pellet for specified amount of time. Higher volumes may require a longer settling time to pellet beads. The default settling time is 2 minutes.
- Drying Time: The drying time after the wash steps can vary depending on your bead products.


---

---


![Materials Needed](https://s3.amazonaws.com/opentrons-protocol-library-website/custom-README-images/customizable-serial-dilution/materials.png)

-- [Opentrons OT-2](http://opentrons.com/ot-2)

-- [Opentrons OT-2 Run App (Version 3.1.2 or later)](http://opentrons.com/ot-app)

-- 200uL or 300 uL Tiprack ([Opentrons tips suggested](https://shop.opentrons.com/collections/opentrons-tips/products/opentrons-300ul-tips-racks-9-600-tips))

-- [12-row automation-friendly trough](https://www.usascientific.com/12-channel-automation-reservoir.aspx)

-- BioRad Plate

---

---

### Time Estimate
* Varies.

## Process
1. Choose the pipette you want to use from the dropdown menu above. ***Note:*** Your pipette should be installed on the ***left mount*** of your OT-2.
2. 

###### Internal
Customizable Serial Dilution, v1

### Additional Notes
Please reference our [Technical Note]() for more information about the expected output of this protocol, in addition to expanded sample data from the Opentrons lab. 

We understand that there are limitations to the use of this protocol, and we plan to make improvements soon. In the meantime, if you'd like to request a more complex dilution workflow, please use our [Protocol Development Request Form](https://opentrons-protocol-dev.paperform.co/). You can also download this Python file and modify it using our [API Documentation](https://docs.opentrons.com/). For additional questions about this protocol, please email support@opentrons.com.
