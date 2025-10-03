<!--
# load-emulator-hardware

<h1 align="center">
LOAD EMULATOR HARDWARE  
  <br>
 
#load-emulator-hardware 
-->
<h1 align="center">
LOAD EMULATOR HARDWARE 
</h1>

<p align="center">
    <a href="#"><img alt="Static Badge" src="https://img.shields.io/badge/status-[2.0]_in%20development-red?style=for-the-badge"></a>
</p>


<details>
    <summary><b>Summary</b></summary>
    <ol>
        <li>
            <a href="#overview">Overview</a>
        </li>
        <li>
            <a href="#repository-organization">Repository Organization</a>
        </li>
        <li>
            <a href="#license">License</a>
        </li>
        <li>
            <a href="#notes">Notes</a>
        </li>
        <li>
            <a href="#references">References</a>
        </li>
    </ol>
</details>

## Overview

The **Load Emulator Hardware** is a project developed with the aim of **simulating electrical loads** for testing nanosatellite modules. It allows for the evaluation of the behavior of systems such as EPS (Electrical Power System) and RE²PS (Reliability Enchanced Eletrical Power System) under different power consumption conditions, without the need for real loads.

The circuit was designed in **KiCad** and uses **LT1492 operational amplifiers**, **transistors**, and **power resistors** to simulate the desired load. This provides flexibility and precision for bench testing.

This project was specifically designed for **ground tests** of the FloripaSat-RE satellites from SpaceLab, targeting the required load demands.

<p align="center">
    <img src="figs/load_emulator_render.png" alt="3D render of Load Emulator PCB">
</p>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=bug"><img alt="Static Badge" src="https://img.shields.io/badge/Report_a_bug-red"></a>
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=enhancement"><img alt="Static Badge" src="https://img.shields.io/badge/Request_a_feature-yellow"></a>
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=question,help+wanted"><img alt="Static Badge" src="https://img.shields.io/badge/Request_help-green"></a>
</p>

## Repository Organization

- `dev/`: Hardware project source files (schematics, PCB layout, and simulations)
- `main/`: Documentation and consolidated hardware releases

## License

_In definition._  

## Notes

Project developed by members of [SpaceLab - UFSC](https://spacelab.ufsc.br), based on the requirements of the XX satellites

## References

- FloripaSat-1 and FloripaSat-2 | SpaceLab - UFSC  
- Developed by: **Fernanda Paiva de Morais**, **Theo M. Vasconcellos** and **João V. Perin** 
- Revised by: **João C. E. Bacelos**

---

