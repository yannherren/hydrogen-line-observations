# 21‑cm Hydrogen Line with RTL‑SDR 🔭🌌

An amateur radio astronomy experiment to detect the galactic 21‑cm HI line (1420.4058 MHz). Data recorded with SDRangel (Radio Astronomy Plugin) and analyzed in a small Jupyter notebook. ✨

![observation](https://github.com/user-attachments/assets/afa15568-9f2d-403f-9fbf-5fc1dcf4bda5)


## Hardware ⚙️
- RTL‑SDR dongle
- Nooelec SAWbird+ H1
- 3D printed 8‑turn helix antenna with 30×30 cm reflector
<p style="float: left">
  <img alt="IMG_4619" height="500" src="https://github.com/user-attachments/assets/42e5ca2d-6edf-438b-8047-7afa617981f6" />
  <img alt="IMG_4620" height="500" src="https://github.com/user-attachments/assets/517e9445-aa49-42cd-8386-880a7c27040e" />
</p>

## Software 💻
- SDRangel + Radio Astronomy Plugin
- Data analysis in a jupyter notebook with numpy, matplotlib, astroquery 

## Data Recording 📡
- Center frequency: 1420.400 MHz
- Sample rate / bandwidth: 2.0 MS/s, 2.0 MHz
- FFT size: 2048
- Integration per spectrum: ~10 minutes
