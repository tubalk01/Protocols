# Nucleic Acid Purification with Magnetic Beads

### Author
[Opentrons](https://opentrons.com/)

## Categories
* Molecular Biology
    * Nucleic Acid Purification

## Description
With this protocol, you can perform high-quality nucleic acid purifcations using magnetic beads and the [Opentrons Magnetic Module](https://shop.opentrons.com/products/magdeck?_ga=2.120183432.1039841802.1542049668-403439593.1535387376). This setup yields high quality PCR product and other nucleic acids without the use of centrifugation or vacuum separation. You can also use this for NGS library cleanup steps.

While we have reagent recommendations in the **Materials Neeeded** section below, you can use any [SPRI magnetic beads](https://bitesizebio.com/13580/solid-phase-reversible-immobilization-how-to-get-a-bead-on-the-clean-up-of-your-ngs-libraries/) you prefer. For more detailed information on how to use this protocol, please see our [Technical Note](INSERT LINK).

---

---

***Setup***

Using the customization fields below, set up your protocol as follows:

-- **Pipette and Mount:** Specify your pipette and mount (left or right). **We recommend the p50 and p300 single or multi-channel pipettes for the volumes of reagents in this experiment.** 

-- **Sample number:** Customize the number of samples to run per protocol. **We recommend multiples of 8 if you are using a multi-channel pipette.**

-- **Sample volume:** Specify the starting volume of the input sample. **We recommend volumes about 10 µL.** 

-- **Bead Ratio:** Customize the ratio of beads for left or right side size-selection of fragments. The default bead ratio is **1.8x the input sample volume.**

-- **Elution Volume:** Specify the final volume to elute the purified nucleic acid. **The Opentrons MagDeck supports elution volumes above 10 µL.**

- **Incubation Time:** Specify the amount of time (in minutes) that the bead solution and input sample interact.

- **Settling Time:** Specify the amount of time needed to pellet the beads. **Higher volumes may require a longer settling time to pellet beads.**

- **Drying Time:** Specify the drying time needed after wash steps.

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
Nucleic Acid Purification, v1

### Additional Notes
Please reference our [Technical Note]() for more information about the expected output of this protocol, in addition to expanded sample data from the Opentrons lab. 

We understand that there are limitations to the use of this protocol and we plan to make improvements soon! In the meantime, if you'd like to request a more complex purification workflow, please use our [Protocol Development Request Form](https://opentrons-protocol-dev.paperform.co/). You can also download the Python file from this page and modify it using our [API Documentation](https://docs.opentrons.com/). For additional questions about this protocol, please email support@opentrons.com.
