![Freya banner](https://github.com/Freya-Vivariums/.github/blob/main/brand/Freya_banner.png?raw=true)

The **Node-RED flow** with the default Freya Vivarium Control System functionality. This can be used as a starting point for your own custom flows.

![Screenshot](documentation/screenshot.png)

## Installation
1. Open [Freya_flows.json](Freya_flows.json) file here on GitHub, and click the `Copy raw file` button.
2. Open your Node-RED editor (usually http://[ip address]:1880).
3. In the top-right menu, select `≡ → Import → Clipboard`.
4. Paste the copied content into the dialog and click `Import`.
5. Click `Deploy` to activate the flow. Check the Debug sidebar or your configured outputs to verify everything is running.
6. Open the `Dashboard` at http://[ip address]/dashboard

## Hardware Requirements
<img src="documentation/wiring.png" align="left" width="30%"/>

This flow assumes the **Freya Vivarium Control System** with the [Freya Sense'n'Drive Hardware Cartridge](https://github.com/Freya-Vivariums/Freya-SenseAndDrive-Hardware-Cartridge) installed in the controller, the [Freya "Terra" Sensor](https://github.com/Freya-Vivariums/Freya-Terra-Sensor) connected to the sensor port and the outputs wired to the different actuators according to the diagram.

