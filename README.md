VERILOG,SYSYTEM VERILOG and UVM
# Digital Design & Verification Repository

This repository contains my work in **Verilog**, **SystemVerilog**, and **UVM** for digital design and verification.

## 📂 Contents
- **Verilog** – RTL designs such as adders, multiplexers, counters, and more.
- **SystemVerilog** – Enhanced designs and testbenches with advanced verification features.
- **UVM** – Reusable, scalable verification environments following the Universal Verification Methodology.

## 🛠 Tools Used
- [Icarus Verilog](http://iverilog.icarus.com/) – Open-source Verilog/SystemVerilog simulator
- [ModelSim / QuestaSim](https://eda.sw.siemens.com/en-US/ic/modelsim/) – Industry-standard simulation tool
- [GTKWave](http://gtkwave.sourceforge.net/) – Waveform viewer
- Any preferred text editor/IDE (VS Code, Sublime, Vim, etc.)

## 🚀 How to Run
1. **Compile RTL & Testbench**
   ```bash
   iverilog -o design.vvp design.v testbench.v
