<h1 align="center">Hey, I'm Joseph 👋</h1>
<p align="center"><b>Embedded systems & biomedical engineer, based in Paris.</b><br><i>I make silicon move things. Come on in, the terminal's warm.</i></p>

---

```console
[    0.000] RCC: HSE 8 MHz, PLL locked @ 100 MHz
[    0.002] boot: joseph-ulrich v2026.10
[    0.004] hw:   STM32 | EFR32 | ESP32 | FPGA
[    0.006] os:   FreeRTOS ok | Zephyr loading [=======>   ] 70%
[    0.009] edu:  Sup Galilée (embedded / biomedical) + ESPRIT (mechatronics)
[    0.011] exp:  STMicroelectronics, Rousset
[    0.013] exp:  Netatmo (C / Zephyr / Zigbee / EFR32)
[    0.015] doc:  fix merged into ST application note AN5795
[    0.016] doc:  2 articles live on ST Wiki (FIR on STM32C5, GPDMA linked-list)
[    0.017] WARN: nylon tendons creep under load. lesson written to flash.
[    0.019] mount: /home/joseph ... ok

  Welcome! Pull up a chair, make yourself at home.

joseph@lab:~$ ls ~/life
3d_printer/  cats/  series/  games/  football/

joseph@lab:~$ cat ~/life/3d_printer/status
Elegoo Neptune 4 on Klipper. Prints robot parts, enclosures,
and the occasional plate of spaghetti. PETG and I are still negotiating.

joseph@lab:~$ cat ~/life/cats/README
Cats: the only coworkers allowed to walk on my keyboard.
Got one? Send a picture, I mean it.

joseph@lab:~$ cat ~/life/series/favorites
series:  <SERIES_1>, <SERIES_2>
actor:   <ACTOR>
anime:   Death Note (team L, always)

joseph@lab:~$ ./games --favorite
<GAME>   // with FC26 and PUBG on rotation

joseph@lab:~$ cat ~/life/football
Real Madrid. Hala Madrid y nada más. ⚪

joseph@lab:~$ echo $OPEN_TO
Embedded, robotics, medtech. And a good chat about any of them._
```

## 🛠️ Things I've built

| Project | What it does | Stack |
|---|---|---|
| **Myoelectric hand prosthesis** | Final-year project: EMG acquisition and embedded signal processing driving tendon-actuated fingers. It didn't fully work, and it taught me more than the projects that did. | STM32, C, EMG front-end |
| **STM32 validation lab** | Personal test automation platform for Arm Cortex-M validation. Caught a DMA glitch on circular ADC transfers and an MDF clock inconsistency. | HAL/LL, ST-Link, oscilloscope, logic analyzer, Python |
| **AN5795 contribution** | That MDF clock finding became a correction to an official STMicroelectronics application note. | STM32 MDF, documentation |
| **[ST Wiki: FIR Signal Processing](https://wiki.st.com/stm32mcu/wiki/Getting_started_with_FIR_Signal_Processing)** | Official ST tutorial I wrote: a real-time ADC → FIR → DAC pipeline on STM32C5, DMA double-buffering, CMSIS-DSP. | STM32C5, NUCLEO-C562RE, CMSIS-DSP |
| **[ST Wiki: GPDMA and Linked-list](https://wiki.st.com/stm32mcu/wiki/Getting_started_with_GPDMA_and_Linked-list)** | Official ST tutorial I wrote: chaining autonomous DMA transfers through linked-list nodes, zero CPU involvement. | STM32H5, GPDMA, STM32CubeMX |
| **30 jours de STM32** | Public LinkedIn series: one STM32 concept a day, explained from scratch. | Teaching, STM32 |

**Currently building:** BMS-VirtualLab, a battery state-of-charge estimator (Extended Kalman Filter on a 2RC model, validated on real LG 18650 data), and a humanoid robot built from recycled printer parts.

## 🧰 Toolbox

**Firmware** &nbsp;
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Zephyr](https://img.shields.io/badge/Zephyr-7929D2?style=flat-square)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2E8B57?style=flat-square)
![Zigbee](https://img.shields.io/badge/Zigbee-EB0443?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**Hardware** &nbsp;
![Altium](https://img.shields.io/badge/Altium-A5915F?style=flat-square)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-444444?style=flat-square)
![Vivado](https://img.shields.io/badge/Vivado-ED1C24?style=flat-square)
![SolidWorks](https://img.shields.io/badge/SolidWorks-E2231A?style=flat-square)

**Test & data** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=flat-square&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 📡 Say hi

[LinkedIn](https://linkedin.com/in/TON-PROFIL) · [Email](mailto:TON-EMAIL)

```c
while (1) {
    learn();
    build();
    break_things();   // then fix them
    pet_cat();
}
```
