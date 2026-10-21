# cellular-robust-quadrotor-drone
That is a fascinating application for this type of custom UAV platform! Integrating mobile network testing gear—such as specialized radio frequency (RF) measurement sensors, data loggers, or scanning receivers—onto a stable multirotor drone allows operators to map and analyze cellular coverage (3G, 4G LTE, and 5G) precisely in low-altitude airspace where traditional ground drive-tests cannot reach.

## **Drone Overview**

* **Type & Design:** A high-performance, custom-designed quadcopter drone shown isolated against a clean, plain white background.


* **Frame Structure:** Features lightweight carbon fiber arms and landing gear connected with 3D-printed grey joiners and central mounting hubs.



## **Key Components**

* **Propulsion System:** Four large propellers mounted on brushless motors with orange accent rings.


* **Camera & Gimbal:** A multi-axis stabilized camera gimbal system mounted directly underneath the main body.


* **Electronics & Battery:** Houses gray electronics enclosures, visible wiring with yellow battery connectors, and an auxiliary electronics board with dual antennas pointing downward between the landing skids.


* **Landing Gear:** Sturdy dual-skid carbon fiber landing gear with protective end caps to ground the frame stably.

<img width="1365" height="768" alt="quadrotor" src="https://github.com/user-attachments/assets/a488eee7-2ab4-4f2e-a355-22f8c9eef227" />

<img width="1600" height="1200" alt="WhatsApp Image 2026-10-21 at 09 18 08" src="https://github.com/user-attachments/assets/e30a27eb-895f-4e81-9a63-a96ab6a98e37" />

<img width="1439" height="1409" src="https://github.com/user-attachments/assets/1109d800-b08d-4462-bb37-a98d1b0ef56b" />

Based on the close-up images of your custom unit, here is a detailed technical overview of the **RF Sensor Payload Module** used for network auditing:

---

## **Hardware & Enclosure Design**

* **Custom 3D-Printed Chassis:** Built with an active cooling slotted rear panel (featuring an integrated exhaust fan grill) and top heat vents to handle high thermal output during extended flights.


* **Modular Multi-Band Antenna Array:** Features multiple high-gain omnidirectional blade/stub antennas mounted via direct SMA/RP-SMA brass bulkhead connectors. The hinged design allows 90° orientation adjustments depending on whether the payload is mounted bottom-down or side-slung.


* **External Connectivity:** Includes an exposed, accessible side USB-A / Data Interface port for rapid field retrieval of logged data, external power input, or local maintenance without opening the sealed casing.


* **Low-Vibration Mounting:** Designed to attach directly underneath the central multirotor frame using quick-release screws or vibration isolators to prevent motor micro-vibrations from disrupting internal circuit boards.



---

## **Functional Capabilities & Data Collection**

* **Multi-Generation Spectrum Scanning:** Passively scans and decodes 3G (UMTS), 4G (LTE), and 5G (NR) cellular frequencies simultaneously across major West African bands (e.g., 700 MHz, 800 MHz, 900 MHz, 1800 MHz, 2100 MHz, 2600 MHz, and 3.5 GHz Sub-6 GHz).


* **Key KPI Logging:**
* **Signal Strength & Quality:** Records precise $RSRP$ (Reference Signal Received Power), $RSRQ$ (Reference Signal Received Quality), $RSSI$, and $SINR$ (Signal-to-Interference-plus-Noise Ratio).
* **Cell Identity:** Identifies serving cell IDs ($PCI/Cell\,ID$), Mobile Country Codes ($MCC$), Mobile Network Codes ($MNC$), and Tracking Area Codes ($TAC$) to map exact cell handovers across operators (e.g., Orange, MTN, Moov in Ivory Coast).


* **3D Elevation & Coverage Profiling:** Combines real-time GPS/GNSS spatial coordinates with RF measurements to produce 3D coverage heatmaps at varying flight altitudes, identifying vertical signal loss or beamforming tilt issues near high-rise structures or complex terrain.

<img width="1080" height="1920" src="https://github.com/user-attachments/assets/7caf47a8-fef4-4a77-80e2-56b723cb63c0" />
<img width="899" height="1599" alt="WhatsApp Image 2026-10-21 at 09 18 10" src="https://github.com/user-attachments/assets/c56e9bac-e3da-409b-a6e9-9dc3a31e98bf" />
<img width="900" height="1600" alt="WhatsApp Image 2026-10-21 at 09 18 10 (2)" src="https://github.com/user-attachments/assets/6a2ae67f-1f3c-49f5-b3b4-7864cff8d02b" />









The breakdown of all key structural, propulsion, avionics, and payload components featured in this design illustrates how each part contributes to conducting precise airborne 3G/4G/5G mobile network measurements:

---

## **1. Telecom Measurement & Sensor Payload**

Located directly underneath the central frame, this dedicated assembly captures real-time cellular signals:

* **White Enclosure Box:** Houses the core processing unit, scanner, or specialized SDR (Software Defined Radio) receiver for multi-band (3G/4G/5G) RF data collection.


* **Downward-Facing Antennas:** Dual black omnidirectional antennas extend beneath the payload to receive cellular signal parameters (RSRP, RSRQ, SINR) without interference from the main body.


* **Exposed Sensor Board & Ports:** An external circuit board provides status LEDs, network connectivity (Ethernet/USB ports), and high-speed data logging connections for live streaming or onboard telemetry storage.



---

## **2. Main Body & Structural Frame**

* **Carbon Fiber Arms & Tubes:** High-rigidity, lightweight carbon fiber tubing provides maximum stiffness with minimal weight to reduce vibrations, which is crucial for high-precision RF mapping.
* **Grey 3D-Printed Structural Hubs:** Molded or 3D-printed grey polymer housings lock the carbon fiber arms to the central deck and house key internal flight controller electronics.


* **Top Canopy / Battery Bay Cover:** A custom grey shroud protects the flight controller, GPS module, and central power distribution system.


* **Side Battery Mounts & Connectors:** Dual side-slung battery trays balance weight evenly; high-current XT60/XT90 connectors and thick silicon wiring supply redundant power.



---

## **3. Camera & Stabilized Gimbal Assembly**

* **Multi-Axis Gimbal:** Mounted on vibration-damping rubber grommets directly beneath the main belly. It actively counteracts movement in pitch, roll, and yaw during flight to keep imagery steady.


* **High-Resolution Optical Camera:** Used alongside cellular data logging to visually inspect cell towers, antenna tilt, azimuth alignments, or line-of-sight obstructions during flight.

---

## **4. Propulsion & Power System**

* **Brushless Motors:** Four heavy-duty motors featuring distinct orange/copper coils drive the aircraft efficiently under high payload capacity.


* **Carbon Composite Propellers:** Two-blade lightweight folding/fixed props designed for high lift and stable hovering performance.


* **Motor Mounts:** Reinforced grey end-caps seamlessly integrate the carbon fiber tube ends with motor mounting plates.



---

## **5. Landing Gear Assembly**

* **Dual-Skid Landing Legs:** Slanted carbon fiber legs provide a wide footprint to safely land on uneven ground without disturbing the delicate lower antennas or camera gimbal.


* **Protective End Caps:** Soft grey rubber caps on the bottom skids cushion impact during landing and protect structural tubes from wear.

<img width="1004" height="565" src="https://github.com/user-attachments/assets/5c108272-83e6-49f6-b701-16be8c559d7e" />
<img width="988" height="556" src="https://github.com/user-attachments/assets/b86251ea-94f0-4fc3-9d4f-1ef073fa321d" />

<img width="2000" height="1125" alt="cellular-quadrotor" src="https://github.com/user-attachments/assets/dc47904a-8be9-4951-bcab-7ca0c2bf9a45" />

Evaluating 3G, 4G, and 5G cellular network data across **Ivory Coast (Côte d'Ivoire)** and broader **West Africa** makes this platform particularly valuable.

In West Africa, rapid telecommunication expansion and diverse terrain present distinct operational challenges and opportunities for airborne network testing:

---

## **Key Applications for Network Evaluation in Ivory Coast & West Africa**

* **Overcoming Challenging Terrain:**
* Ground-based drive testing in regions with dense rainforests, lagoons (such as around Abidjan, Assinie, Assoindé, Gonzaqueville and Yamoussoukro), or rural terrain can be slow and limited.
* Flying this drone allows operators to easily capture 3D signal propagation profiles over impassable ground, dense vegetation, or remote installations.


* **Cell Tower & Antenna Auditing:**
* **Azimuth & Tilt Verification:** The onboard high-resolution camera enables visual inspection of radio antennas mounted on cell towers, verifying whether mechanical tilt, direction (azimuth), or physical damage align with planning models.
* **3D Coverage Mapping:** Airborne RF scanners measure signal parameters (RSRP, RSRQ, SINR) at varying altitudes, mapping vertical coverage for high-density urban areas or future aerial device connectivity.


* **Evaluating 3G, 4G, and 5G Coexistence:**
* In markets transitioning to 5G while maintaining legacy 3G and 4G LTE infrastructure, airborne measurement helps detect inter-technology interference, spectrum overlap, and blind spots near cell boundaries.


* **Rapid Infrastructure Audits:**
* Helps telecom operators, network regulators (such as ARTCI in Ivory Coast), and infrastructure companies inspect tower status, optimize coverage, and audit Quality of Service (QoS) rapidly across urban centers and rural corridors.

https://github.com/user-attachments/assets/10e7887e-17fc-49a5-be65-50ce2542edb5






