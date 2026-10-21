DAY 2 ASSIGNMENT

POWER SUPPLY SYSTEMS

Topic: SMPS, UPS and Power Connectors

Task 1: Devices Using SMPS and UPS

A. Three devices that use SMPS (Switched Mode Power Supply)

1. Desktop Computer: Uses an SMPS to convert AC electricity into regulated DC power required by the motherboard, processor, storage drives and other components.
2. Laptop Charger: Uses an SMPS to convert AC mains electricity into the appropriate DC voltage needed to charge the laptop battery and power the laptop.
3. LED Television: Uses an SMPS to provide different regulated DC voltages for the display, audio system and internal circuits.

B. Two devices that use UPS (Uninterruptible Power Supply)

1. Desktop Computer: A UPS provides temporary battery power during a power cut, allowing the user to save work and shut down the computer safely.
2. Wi-Fi Router: A UPS keeps the router running during a power interruption so that the internet connection can remain available, provided the network service itself is still active.

Task 2: Diagram of a Typical PC SMPS

Main internal components and their functions

1. AC Input: Receives alternating current from the mains electricity supply.
2. EMI Filter: Reduces electrical interference entering or leaving the power supply.
3. Rectifier: Converts AC into pulsating DC.
4. Smoothing Capacitor: Reduces fluctuations in the rectified DC voltage.
5. Switching Circuit: Switches the DC at high frequency.
6. High-Frequency Transformer: Transfers energy and provides electrical isolation while changing the voltage.
7. Secondary Rectifier and Filter: Converts the transformer’s high-frequency output into smooth DC.
8. Regulation and Protection Circuit: Maintains stable output voltages and helps protect against electrical faults.
9. DC Output: Supplies regulated +12 V, +5 V and +3.3 V outputs, as required by the PC components.

Block diagram

        AC MAINS INPUT
               |
               v
          EMI FILTER
               |
               v
           RECTIFIER
               |
               v
      SMOOTHING CAPACITOR
               |
               v
       HIGH-FREQUENCY
       SWITCHING CIRCUIT
               |
               v
    HIGH-FREQUENCY TRANSFORMER
               |
               v
      SECONDARY RECTIFIER
               |
               v
        OUTPUT FILTER
               |
               v
      REGULATED DC OUTPUT
        +12 V / +5 V / +3.3 V
               |
               v
       PC COMPONENTS

Note: A typical modern PC SMPS also has feedback control, protection circuits and, in many designs, active power-factor correction (PFC). The diagram is a simplified functional block diagram.

Task 3: Power Connectors, Their Uses and Safety Tips

1. ATX 24-pin Motherboard Connector

* Description: A large, rectangular connector with 24 pins.
* Devices powered: Supplies the motherboard with its main power rails.
* Safety tip: Align the connector with the motherboard socket and push until the locking clip clicks into place. Never force it.

Paste or draw: A picture of an ATX 24-pin motherboard power connector.

2. SATA Power Connector

* Description: A flat, 15-pin connector with an L-shaped key.
* Devices powered: SATA hard disk drives (HDDs), SATA solid-state drives (SSDs) and compatible optical drives.
* Safety tip: Match the L-shaped key before connecting or disconnecting the cable. Do not pull the cable forcefully.

Paste or draw: A picture of a SATA power connector.

3. Molex 4-pin Connector

* Description: A four-pin peripheral power connector, commonly used in older computer systems.
* Devices powered: Older IDE hard drives, some optical drives, fans and certain accessories.
* Safety tip: Switch off and unplug the computer before connecting or disconnecting the connector. Check its orientation and avoid bending the pins.

Paste or draw: A picture of a 4-pin Molex peripheral power connector.

4. PCIe 6-pin / 8-pin Graphics Card Connector

* Description: A 6-pin or 8-pin auxiliary power connector, sometimes supplied as a 6+2-pin connector.
* Devices powered: Provides additional power to compatible graphics cards.
* Safety tip: Use the correct PCIe power cable from the PSU. Never confuse it with a CPU/EPS connector, and never force it into the socket.

Paste or draw: Pictures of PCIe 6-pin and 8-pin graphics card power connectors.

Task 4: Connecting the SMPS in a New Gaming PC

The following steps explain how to connect a power supply to the motherboard, graphics card and storage devices safely.

1. Switch off the power: Turn off the PSU, unplug the computer from the wall socket and work on a clean, dry surface. Use appropriate ESD precautions.
2. Install the SMPS: Place the PSU in its designated case compartment and secure it with screws. Ensure its fan has adequate ventilation.
3. Connect the motherboard: Attach the 24-pin ATX power cable to the motherboard’s main power socket.
4. Connect CPU power: Attach the 4+4-pin CPU/EPS cable to the motherboard’s CPU power socket near the processor.
5. Connect the graphics card: If required, attach the correct PCIe 6-pin, 8-pin or 6+2-pin cable. For graphics cards with a 12V-2x6 connector, follow the manufacturer’s instructions and use the specified compatible cable.
6. Connect storage devices: Attach SATA power cables to SATA HDDs, SSDs and other compatible drives. Connect a SATA data cable from each SATA drive to the motherboard as well.
7. Connect other peripherals: Connect compatible case fans, hubs and accessories using the appropriate power connectors.
8. Check all connections: Ensure every connector is correctly aligned and fully seated. Keep cables away from fans and hot components.
9. Perform a final inspection: Check that no loose screws or cables obstruct the fans. Confirm that the PSU’s power rating is suitable for the system.
10. Start the PC: Close the case, reconnect the power cable and switch on the PSU. Start the computer and check that it boots normally.

Important safety precautions

* Never open the PSU casing because its capacitors may retain dangerous voltage.
* Never connect or disconnect internal power cables while the system is powered.
* Use only compatible modular cables supplied or explicitly approved for the exact PSU model. Modular PSU cables are not universally interchangeable.
* Follow the motherboard, graphics card and PSU manufacturers’ instructions.

Conclusion

An SMPS provides regulated DC power to computer components, while a UPS supplies temporary backup power during an outage. Correctly identifying power connectors and following safe installation procedures helps ensure reliable computer operation and prevents damage to hardware.
