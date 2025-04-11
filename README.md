# load-emulator-hardware
<h1 align="center">
LOAD EMULATOR HARDWARE  
  <br>
#load-emulator-hardware

<h1 align="center">
LOAD EMULATOR HARDWARE
</h1>

<p align="center">
    <a href="#"><img alt="Static Badge" src="https://img.shields.io/badge/status-em_teste-yellow"></a>
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

O **Load Emulator Hardware** é um projeto desenvolvido com o objetivo de **simular cargas elétricas** para a realização de testes em módulos de nanosatélites. Ele permite a avaliação do comportamento de sistemas como o EPS (Electrical Power System) em diferentes condições de consumo, sem a necessidade de cargas reais.

O circuito foi desenvolvido no **KiCad** e emprega **amplificadores operacionais LM318**, **transistores** e **resistores de potência** para simular a carga desejada. O que permite flexibilidade e precisão nos testes de bancada.

Este projeto foi pensado especialmente para **testes em solo** dos satélites FloripaSat-RE , do SpaceLab. Visando as demandas de carga desejadas. 

<p align="center">
    <img src="figs/load_emulator_render.png" alt="3D render of Load Emulator PCB">
</p>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=bug"><img alt="Static Badge" src="https://img.shields.io/badge/Report_a_bug-red"></a>
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=enhancement"><img alt="Static Badge" src="https://img.shields.io/badge/Request_a_feature-yellow"></a>
    <a href="https://github.com/spacelab-ufsc/load-emulator-hardware/issues/new?labels=question,help+wanted"><img alt="Static Badge" src="https://img.shields.io/badge/Request_help-green"></a>
</p>

## Repository Organization

- `dev/`: arquivos-fonte do projeto de hardware (esquemáticos, layout e simulações)
- `main/`: documentação e versões consolidadas do hardware

## License

_Em definição._  

## Notes

Projeto desenvolvido por membros do [SpaceLab - UFSC](https://spacelab.ufsc.br), com base nas necessidades dos satélites FloripaSat.

## References

- FloripaSat-1 e FloripaSat-2 – SpaceLab / UFSC  
- Desenvolvido por: **Fernanda Paiva de Morais** e **Theo M. Vasconcellos**  
- Revisão por: **João C. E. Bacelos**

---

