\# APMS Component Reference



\## Introduction



This document provides a technical reference for components

identified in the APMS monitor documentation.



The information is based on the APMS project manual.



\## Component Documentation



| Component | Reference | Function | Datasheet |

|---|---|---|---|

| Arduino Nano Every | - | Microcontroller | \[Official datasheet](https://docs.arduino.cc/resources/datasheets/ABX00028-datasheet.pdf) ||

| SIM800L | - | GSM communication | Exact module variant to be verified |

| LM2596 | - | DC-DC step-down voltage regulation | \[Official TI datasheet](https://www.ti.com/lit/ds/symlink/lm2596.pdf) |

| K7805 | - | 5 | K7805 | - | 5 V DC-DC voltage regulation | \[Mornsun K78XX datasheet](https://www.mantech.co.za/Datasheets/Products/K78XX-1000.pdf) |

| LM35 | U5 | Temperature sensing | \[Official Texas Instruments datasheet](https://www.ti.com/lit/ds/symlink/lm35.pdf) |

| Logic level shifter | U6 | Logic-level interfacing | Exact part number to be confirmed |

| NPN transistor | Q1 | Transistor switching / signal interfacing | Exact part number to be confirmed |

| Transistor | Q2 | Buzzer switching and control | Exact part number to be confirmed |

| Schottky diode | D2 | Reverse-current protection / circuit protection | Exact part number too be confirmed |

| Zener diode | D1 | Voltage regulation and circuit protection | Exact part number and voltage rating to be confirmed |

| Trimpot (variable resistor) | RV1 | Adjustable resistance for circuit calibration | Exact part number not identified |



\## References



Primary source: APMS Project Manual.



Exact manufacturer part numbers and datasheets will be

added after component variants are verified.



\## How to Use This Reference



This component reference provides an overview of the electronic components identified in the APMS monitor circuit documentation.



Each entry includes:



\- \*\*Component:\*\* The component name or general component type.

\- \*\*Reference designator:\*\* The identifier used to locate the component in the circuit, such as U5, Q1 or D1.

\- \*\*Function:\*\* The component's documented or intended role in the circuit.

\- \*\*Datasheet or identification:\*\* A datasheet link, verified part information or a note indicating where the exact component specification is still unknown.



\### Component Identification



Reference designators help distinguish individual components within a circuit:



\- \*\*U:\*\* Integrated circuits and electronic modules.

\- \*\*Q:\*\* Transistors.

\- \*\*D:\*\* Diodes.

\- \*\*R:\*\* Resistors.

\- \*\*C:\*\* Capacitors.

\- \*\*RV:\*\* Variable resistors or trimpots.



\### Verification Notes



A component's general type does not always identify its exact manufacturer or part number. Where the available documentation does not establish the precise component specification, the reference explicitly indicates that further identification is required.



Datasheets should therefore be treated as references for the identified component family, not automatic confirmation of the exact hardware fitted to the PCB.

