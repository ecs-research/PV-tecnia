# PV-tecnia
**PV-tecnia** ([https://pvtecnia.com](https://pvtecnia.com)) is a free photovoltaic software provided as an online service (SaaS), capable of creating, planning and simulating the physical and electrical parameters of PV modules, PV arrays, inverters, batteries, locations, consumption profiles and full PV systems.

<img width="100%" height="100%" alt="PV-tecnia" src="https://github.com/user-attachments/assets/dc138e0e-f001-447c-b549-c1d1611ff69c" />

### Key features:

- Capable of creating from the scratch, model and simulate the full PV system chain, including the installation custom consumption profile, the location meteo characteristics, the PV modules used, the PV arrays mounted, an inverter and, optionally, a storage bank:

  <p align="center"><img width="100%" height="100%" alt="Visualising a modelled PV system (full chain) created with PV-tecnia" src="https://github.com/user-attachments/assets/2e65a7b9-4b11-44c3-83b7-9b7306d8ccf4" /><br><em>Visualising a modelled PV system (full chain) created with PV-tecnia</em></p>

- Supports the creation of systems with N arrays (mixing different layouts and configurations), 1 DC/AC inverter and 1 storage bank (with multiple batteries):

  <p align="center"><img width="70%" height="70%" alt="Creating a PV array with PV-tecnia" src="https://github.com/user-attachments/assets/715b000a-acf2-4d11-b1ae-5ace4c172f7d" /><br><em>Creating a PV array with PV-tecnia</em></p>
  <p align="center"><img width="70%" height="70%" alt="Visualising the I-V and P-V curves of a PV array affected by shading" src="https://github.com/user-attachments/assets/b0469306-22a9-4943-ab9f-83b47fda3444" /><br><em>Visualising the I-V and P-V curves of a PV array affected by shading</em></p>

- Offers a huge database of PV elements:
  - **42000 modules** from CEC, Sandia and PAN databases.
  - **11000 inverters** from CEC, ADR and OND databases.
  - **800 batteries** from CEC and BTR databases.

  <p align="center"><img width="70%" height="70%" alt="Interface to search for PV modules in the PV-tecnia databases" src="https://github.com/user-attachments/assets/3a9b949c-3e5e-430d-b45d-36e3d18069c7" /><br><em>Interface to search for PV modules in the PV-tecnia databases</em></p>

- User can register its own consumption profiles, locations, PV modules, inverters and batteries, by entering their physical and electrical parameters, analysing their behaviour individually:

  <p align="center"><img width="70%" height="70%" alt="Example of single home (residential) consumption profile created with PV-tecnia" src="https://github.com/user-attachments/assets/e84404a1-c8ec-44a4-bdcf-4dd766b2a451" /><br><em>Example of single home (residential) consumption profile created with PV-tecnia</em></p>

- PV modules and PV arrays analysis includes: DC-out power, I-V and P-V curves, computed under the SDM (single diode model) for several global POA irradiances and different panel cell temperatures:

  <p align="center"><img width="70%" height="70%" alt="Example of PV module analysis (PAN database)" src="https://github.com/user-attachments/assets/4a9c2a65-1edf-4d00-a458-e63480a5bb43" /><br><em>Example of PV module analysis (PAN database)</em></p>

- PV arrays analysis also includes the shading characteristics of the array (its impact in the array I-V and P-V curves), and most common array losses (shading losses, thermal losses, irradiance losses, module nameplate quality losses, mismatch losses, array connections losses, DC wiring losses, soiling losses, ageing losses, LID losses, IAM losses, light soaking losses, spectral losses, unavailability losses, snow losses, etc):

  <p align="center"><img width="70%" height="70%" alt="Example of PV array analysis" src="https://github.com/user-attachments/assets/67f7b59a-7531-47b2-9835-a35feec5230e" /><br><em>Example of PV array analysis</em></p>

- Inverters analysis includes: efficiency and AC-out power variation curves (versus DC-in power, DC-in current and DC-in voltage):

  <p align="center"><img width="70%" height="70%" alt="Example of PV inverter analysis (OND database)" src="https://github.com/user-attachments/assets/ff5bb702-f6a0-4734-bba9-293194d8021a" /><br><em>Example of PV inverter analysis (OND database)</em></p>

- Batteries analysis includes: time series variation of state-of-charge (SoC, when charging), depth-of-discharge (DoD, when discharging), current, voltage, capacity and temperature, the battery voltage variation versus the SoC / DoD states and the capacity, for different input change or output discharge power flows, and the battery performance parameters (capacity reduction variation as the number of charge/discharge cycles increases and as the temperature drops):

  <p align="center"><img width="70%" height="70%" alt="Example of PV battery analysis (BTR database)" src="https://github.com/user-attachments/assets/a2f6e613-3f0a-489c-becf-661f0d208de0" /><br><em>Example of PV battery analysis (BTR database)</em></p>

- Full system chain analysis includes: yearly, monthly and daily time series variation of PV-out (generation), battery-out (discharge), grid-out (supply), load-in (consumption), battery-in (charge), grid-in (injection), inverter-in (night-tare) powers, all combinations of power-flow (PV to load, PV to battery, PV to grid, battery to load, grid to inverter, grid to load), the DC and max AC powers (Pmp / PacMax) of the whole system, the DC power, short circuit current (Isc), open circuit voltage (Voc), max power current and voltage (Imp / Vmp), overall losses, self-shaded and inter-shaded fractions, POA irradiances, cell temperatures and angle of incidence (AOI) of every mount of the system, and some financial parameters (annual saved money and payback years based on the installation costs and the grid-in/out KWh electricity prices):

  <p align="center"><img width="70%" height="70%" alt="Example of selection of mounts from a simulated PV system" src="https://github.com/user-attachments/assets/faf174bc-5455-4de6-a013-1dab0f255041" /><br><em>Example of selection of mounts from a simulated PV system</em></p>

- Location analysis includes: yearly, monthly and daily time series variation of the POA irradiances (global, direct, diffuse, sky-diffuse, ground-diffuse), the global horizontal, diffuse horizontal, direct beam and direct extraterrestial irradiances, the cell temperature (under different models, open rack & close-mount glass-glass, glass-polymer, freestanding, insulated, etc), the air temperature, the AOI, the humidity, the wind speed and direction and the air mass:

  <p align="center"><img width="70%" height="70%" alt="Interface to select and view the meteo characteristics of a location for the PV system" src="https://github.com/user-attachments/assets/97665321-58d9-4901-a2ed-671ed7a28bd8" /><br><em>Interface to select and view the meteo characteristics of a location for the PV system</em></p>

- PV-tecnia is accesible from any web browser at [https://pvtecnia.com](https://pvtecnia.com). Adapted to desktop and smartphone devices. No software installation is needed.

  <p align="center"><img width="45%" height="45%" alt="PV-tecnia usage from a smartphone device" src="https://github.com/user-attachments/assets/c9a8201b-bfd6-477f-8726-372681b94c55" /><br><em>PV-tecnia usage from a smartphone device</em></p>

### What about the code:

- This project doest not have published code yet.
- The code may be available upon request/private license (<contact@pvtecnia.com>).

### Samples in action:

- **Desktop version** ([Youtube video](https://youtu.be/wBsqdLPJfKw?si=syvrZr-h99gu7We-)): PV-tecnia usage from a web-browser, handling a simulated 33 KW photovoltaic system, installed in a university building in Spain. The system consists of 8 mount arrays (every one with 13x1 LONGi modules, 340 Wp each), oriented 188º from north towards east and tilted 25º, and 1 Huawei DC/AC inverter (tri-phase). No battery storage bank is added. The system produces 50.8 MWh yearly (6.4 MWh per mount).



- **Smartphone version** ([Youtube video](https://youtu.be/kSJufF1AO2s?si=OKGveYCazepUbuUh)): PV-tecnia usage from a mobile device, handling a simulated 50 KW photovoltaic system, installed in an industrial plant in Spain. The system consists of 8 mount arrays (every one with 7x4 Exiom modules, 260 Wp each), oriented 128º from north towards east and tilted 38º, and 1 Afore DC/AC inverter (tri-phase). No battery storage bank is added. The system produces 74.96 MWh yearly (9.1 MWh per mount).

### More links:

- [LinkedIn](https://linkedin.com/company/pv-tecnia/)
- [Twitter/X](https://x.com/PVTecnia/)
