# Hi, I'm Vanshaj 👋

**Instrumentation & Test Automation | Python · PyVISA/SCPI · OPC-UA**

I build software that automates real measurement hardware — replacing manual/LabVIEW-style workflows with Python-driven acquisition, GUI, and analysis pipelines. Currently in my final year, aiming for a role in industrial automation / test & measurement (T&M).

---

### 🔧 What I've built

**[AH2700A Automated Measurement Suite](https://github.com/vanshajvr/scientific-measurement-automation-suite)**
At CSIR-NPL (India's National Metrology Institute), I built an automated instrumentation suite driving an AH2700A capacitance bridge, a dielectric test fixture, and a Fluke thermo-hygrometer over PyVISA/SCPI — replacing a manual/LabVIEW workflow. It includes a 3-tab Tkinter GUI (live dashboard, time-series/frequency-sweep acquisition, statistical & uncertainty analysis).

Over 48 days I collected 134,806 raw measurements across 57 CSV files. A few results from that data:
- Data cleaning reduced measurement noise (std dev) by **~125x** (74,429 ppm → 595 ppm)
- Found environmental drift (temperature/RH), not instrument noise, dominates sub-pF measurement uncertainty (RH–Cp correlation r = 0.959)
- Ran a GUM-aligned Monte Carlo uncertainty evaluation: combined standard uncertainty ~568.7 aF, expanded uncertainty (k=2) ~1.14 fF

**[MEMS – Metrology Experiment Management System](https://github.com/vanshajvr/mems)**
A FastAPI + SQLAlchemy backend for managing research projects, experiments, datasets, and analysis — built to reuse the real CSV schema from the AH2700A work. Projects → Experiments → Datasets → Analysis, fully relational.

**🚧 In progress: instrument-agnostic automation framework**
A generalized driver-template system (loosely modeled on the IVI class-driver pattern) so a measurement suite isn't locked to one instrument. Building out an AH2700A driver first, then adding an OPC-UA bridge (via `asyncua`) to expose live measurement data as a second output alongside CSV logging.

---

### 🧰 Toolbox

`Python` `PyVISA` `SCPI` `FastAPI` `SQLAlchemy` `Pydantic` `Tkinter` `OPC-UA (asyncua)` `Pandas/NumPy` `Data Acquisition` `Measurement Uncertainty (GUM)`

---

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/vanshaj-verma-538b39197) · [X/Twitter](https://twitter.com/vanshajverma60)
