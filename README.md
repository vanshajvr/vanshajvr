# Hi, I'm Vanshaj 👋

**Instrumentation & Test Automation | Python · PyVISA/SCPI · OPC-UA**

I build software that automates real measurement hardware — replacing manual/LabVIEW-style workflows with Python-driven acquisition, GUI, and analysis pipelines. Currently in my final year, aiming for a role in industrial automation / test & measurement (T&M).

---

### 🔧 What I've built

**Automated Capacitance Bridge Measurement Suite**
Built an automated instrumentation suite driving a precision capacitance bridge, a dielectric test fixture, and an environmental (temperature/humidity) sensor over PyVISA/SCPI — replacing a manual, LabVIEW-style workflow. Includes a 3-tab Tkinter GUI (live dashboard, time-series/frequency-sweep acquisition, statistical & uncertainty analysis) and a full measurement-uncertainty pipeline following standard metrology practice (GUM-aligned Monte Carlo evaluation).

**MEMS – Metrology Experiment Management System**
A FastAPI + SQLAlchemy backend for managing research projects, experiments, datasets, and analysis. Projects → Experiments → Datasets → Analysis, fully relational.

**🚧 In progress: instrument-agnostic automation framework**
A generalized driver-template system (loosely modeled on the IVI class-driver pattern) so a measurement suite isn't locked to one instrument. Building out a capacitance-bridge driver first, then adding an OPC-UA bridge (via `asyncua`) to expose live measurement data as a second output alongside CSV logging.

---

### 🧰 Toolbox

`Python` `PyVISA` `SCPI` `FastAPI` `SQLAlchemy` `Pydantic` `Tkinter` `OPC-UA (asyncua)` `Pandas/NumPy` `Data Acquisition` `Measurement Uncertainty (GUM)`

---

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/vanshaj-verma-538b39197) · [X/Twitter](https://twitter.com/vanshajverma60)
