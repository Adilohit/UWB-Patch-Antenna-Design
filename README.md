# UWB Patch Antenna for 5G Applications

## Overview
This project involves the design and simulation of an Ultra-Wideband (UWB) microstrip patch antenna intended for 5G sub-6 GHz communication and the full UWB range (3.1–10.6 GHz). The goal was to build a compact antenna with wide bandwidth coverage, good radiation efficiency, and interference suppression using dual notch structures.

The antenna was modeled and analyzed using Ansys HFSS. Key parameters such as return loss, mutual coupling, gain, radiation patterns, and efficiency were evaluated to validate performance across the target frequency bands.

---

## Project Objective
- Support the 3.3–4.2 GHz 5G band and complete UWB range.
- Achieve return loss below −10 dB across most of the band.
- Reduce interference from WLAN (5.2–5.8 GHz) and INSAT/Super-Extended C-band.
- Evaluate suitability for MIMO use by analyzing isolation (S12/S21) and port behavior.

---

## Design Approach
The antenna structure is based on a compact microstrip patch, with modified L-shaped slots to introduce dual notch bands. Slot geometry and feed dimensions were optimized through simulation sweeps to achieve strong interference rejection and stable wideband performance. The feedline was tuned for proper impedance matching to reduce reflection and improve power transfer.

---

## Simulation Results

### Return Loss (S11)
Shows multiple resonances across the operating range with values below −10 dB, confirming strong impedance matching.

<img width="1059" height="490" alt="Screenshot 2024-11-07 222603" src="https://github.com/user-attachments/assets/6b3f1696-321d-43db-803d-0a261478730e" />


### Isolation & S-Parameters (S12 / S21)
Isolation remains below −20 dB over major portions of the frequency range, supporting MIMO usage.

<img width="1064" height="505" alt="Screenshot 2024-11-07 222535" src="https://github.com/user-attachments/assets/dc65a769-8883-4ea9-bfca-7e3566179893" />


### 3D Gain Plot
The 3D gain surface shows a bi-directional figure-8 radiation pattern, peaking around 5 dB and with deep nulls at ±90°.

<img width="686" height="486" alt="Screenshot 2024-11-07 224214" src="https://github.com/user-attachments/assets/6283b994-7173-4ed7-b80c-610af2fb0e4a" />


### Realized Efficiency (rE)
Efficiency pattern follows the same figure-8 distribution, peaking near 0 dB in primary directions.

<img width="640" height="461" alt="Screenshot 2024-11-07 223804" src="https://github.com/user-attachments/assets/38237f31-3143-424e-ae99-c22aa4303816" />


### Polar Radiation Pattern
Shows symmetrical bi-directional behavior and good front-to-back performance.

 <img width="590" height="445" alt="Screenshot 2024-11-07 224329" src="https://github.com/user-attachments/assets/8ef0a3f5-572e-4571-a683-f88bca1e2c47" />



### HFSS Final Structure
Visual representation of the antenna model and surrounding airbox.

<img width="724" height="502" alt="Screenshot 2024-11-07 223511" src="https://github.com/user-attachments/assets/afb0e33a-8dd0-4186-8082-ca2966c435a7" />

<img width="723" height="510" alt="Screenshot 2024-11-07 223540" src="https://github.com/user-attachments/assets/ef6993aa-9b73-4ba8-8435-58994e04010f" />



---

## Conclusion
The designed UWB antenna covers the full UWB range (3.1–10.6 GHz) and aligns well with requirements for 5G sub-6 GHz operation. The dual-notch structure effectively suppresses interference from WLAN and INSAT bands, improving signal clarity. Bi-directional radiation and strong port-to-port isolation make the design suitable for point-to-point links and MIMO systems. Compact size supports integration in portable wireless hardware.

---

## Future Work
- Explore miniaturization using fractal geometries or metamaterials.
- Add beamforming support through phased array configurations.
- Fabricate the antenna and compare real vs simulated performance.

---

## Tools Used
- Ansys HFSS 2024 R2 (Student Version)
