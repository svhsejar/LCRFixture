# HP Multi-frequency LCR Adapter

This project provides the documentation and build details for a custom-built interface adapter designed for use with the **HP 4274A** and **HP 4275A** Multi-frequency LCR Meters. 

The adapter converts the standard four-terminal pair BNC outputs of the LCR meter into standard binding posts/banana jacks, allowing for easy connection of discrete components, test leads, or custom fixtures while maintaining shielding and signal integrity.

## Hardware Overview
The build is housed in a rugged die-cast aluminum enclosure to provide excellent RF shielding, which is critical for the high-frequency measurements supported by the 4275A. The internal wiring follows a Kelvin sensing (4-wire) configuration to ensure measurement accuracy.

### Project Photos
Below are the reference images for the completed assembly:

![Internal Wiring](./images/internal_wiring.jpg)
*Internal layout and shielding*

![Finished Box](./images/finished_box.jpg)
*Completed adapter with BNC and Binding Post interfaces*

## Bill of Materials (BOM)

| Component | Model / Part Number | Description | Quantity |
| :--- | :--- | :--- | :--- |
| **Enclosure** | Pro'sKit 900-162B | Die Cast Aluminum Box | 1 |
| **BNC Connectors** | Model 2447 & 2447A | BNC (M) Panel Mount Connectors | 4 |
| **Banana Jacks** | Model 3750, 3760 & 3770 | Standard Binding Posts (Red, Black, Green) | 1 Set |
| **Wiring** | 20 AWG / Coaxial | Internal interconnects | As req. |

## Fabrication

### Drilling Template
To ensure precise alignment of the BNC connectors and binding posts, please refer to the technical drawing files. Precision is required to match the fixed spacing of the HP LCR meter front panel terminals.

* [Download Drilling Template (PDF/DXF)](./drawings/drilling_template.pdf)

## Compatibility
This adapter is specifically designed for:
* **HP 4274A:** Multi-frequency LCR Meter (100Hz - 100kHz)
* **HP 4275A:** Multi-frequency LCR Meter (10kHz - 10MHz)

## License
This project is shared for educational and hobbyist use.