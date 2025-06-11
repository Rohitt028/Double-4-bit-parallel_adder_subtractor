# Double-4-bit-parallel_adder_subtractor
"Double 4-bit Parallel Adder/Subtractor in Verilog HDL 


**Author:** Rohit Itware  
**Tool Used:** Xilinx Vivado 2025.2 (Simulation Only)

## 📝 Description:
This project implements a **Double 4-bit Parallel Adder/Subtractor** in Verilog HDL.  
The design performs either addition or subtraction based on a control signal (`M`). The module has been tested using a Verilog testbench and simulated in **Vivado 2025.2**.

## 📂 File Structure:

| File Name                  | Description                               |
|---------------------------|-------------------------------------------|
| `adder_subtractor.v`       | Verilog source code for Double 4-bit Adder/Subtractor |
| `adder_subtractor_tb.v`    | Testbench for functional simulation of `adder_subtractor.v` |
| `simulation/`              | Contains simulation waveform screenshots (`op1.png`, `op2.png`) |

## ⚙️ How to Simulate in Vivado 2025.2:

1. Open Vivado and create a new RTL project.
2. Add the following files:
   - `adder_subtractor.v`
   - `adder_subtractor_tb.v`
3. Set `adder_subtractor_tb.v` as the **top module**.
4. Run **Behavioral Simulation**.
5. View output waveforms (or check the provided screenshots in the `/simulation/` folder).

## 🖥️ Module I/O Ports:

| Signal | Direction | Width  | Description                      |
|--------|----------|--------|----------------------------------|
| A      | Input    | 4-bit  | First operand                    |
| B      | Input    | 4-bit  | Second operand                   |
| M      | Input    | 1-bit  | Mode Select (0 = Add, 1 = Subtract) |
| Cin    | Input    | 1-bit  | Carry input                      |
| S      | Output   | 4-bit  | Sum/Difference output             |
| Cout   | Output   | 1-bit  | Carry/Borrow output               |

## ✅ Simulation Output:

Waveform screenshots for both addition and subtraction operations are provided in the `/simulation/` folder:
- `op1.png`: Addition result
- `op2.png`: Subtraction result  

## ⚠️ Notes:

- This design is **for simulation purposes only**.
- No synthesis or FPGA constraints (`.xdc`) are provided.
- Verified using **Vivado 2025.2 Behavioral Simulation**.

## 📌 Author:

[Rohit Itware](https://github.com/Rohitt028)
