Penning Trap Experiment
This repository contains documentation and initial setup configurations for operating a Penning Trap experiment. The experiment is divided into three phases:

Ion Injection
Ion Storage
Measurement and Readout
Devices and Usage
PDT Switch (Stahl HV 1000, customized for ARTEMIS)

Controls high-voltage pulsing required during ion injection.
Power supply details pending.
Sickler Lens

Focuses and shapes the injected ion beam.
Powered by CAEN high-voltage supply.
Voltage Source for CT (Stahl HV‐250‐8)

Provides the necessary trap voltage for storing ions.
Cryogenic Biasing & PID Regulator (Stahl BS-1-10 Cryo)

Maintains low temperatures and stable bias conditions for amplifiers and electronics in the trap.
Pulse/Delay Generator (Berkeley Nucleonics Model 575)

Used for generating precise timing signals and time-tagging during measurements (DreEBIT and ARTEMIS).
Repository Structure
docs/
Contains documentation, flowcharts, and references.
config/
Example configuration files for each device (where available).
scripts/
Basic scripts or code snippets to interface with the devices (if applicable).
README.md
This file.
How to Use
Review Device Interconnections

Familiarize yourself with the flowchart in docs for a high-level overview of how the devices are interconnected across each experimental phase.
Set Up Power Supplies

Ensure the PDT Switch and Sickler Lens power supplies are correct and stable before injection.
Configure Trap Voltages

Use the Stahl HV-250-8 to establish the central trap potential.
Enable Cryogenic Operation

Set up and tune the cryogenic biasing and PID regulator (Stahl BS-1-10 Cryo) to maintain low-temperature conditions.
Coordinate Timing

Adjust the pulse/delay parameters (Berkeley Nucleonics Model 575) to align with the desired measurement cycle.
Run Measurements

Use the scripts in scripts/ (if provided) or external DAQ software to collect and analyze ion signals.
Contributing
Please submit pull requests for any fixes or improvements in device configuration, documentation, or scripts.
Follow the project’s coding and documentation standards to maintain consistency.
License
This project is released under MIT License. See the LICENSE file for more details.
