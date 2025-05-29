**Name: SHREEDHAR KUMAR K.J**

**REGISTER NO: 212224230265**

### EX NO: 5 - SERIAL IN SERIAL OUT SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**PROCEDURE**

### 1. Open Quartus Software
Launch **Quartus Prime** on your system.

### 2. Create a New Project
- Navigate to **File > New Project Wizard**.
- Set your **project directory**, **project name**, and **top-level entity name**.
- Add your **Verilog (.v)** or **VHDL (.vhd)** source file.
- Select the correct **FPGA device** based on your target board.

### 3. Add Design Code
- Open your top-level module (e.g., `main.v`).
- Paste or write your Verilog/VHDL design.

### 4. Compile the Design
- Go to **Processing > Start Compilation**.
- Wait until the compilation process is complete.
- Resolve any errors or warnings if present.

### 5. Generate RTL Schematic
- Navigate to **Tools > Netlist Viewers > RTL Viewer**.
- View the generated RTL schematic.
- Save the schematic using **File > Export** (as image or PDF).

### 6. Assign I/O Pins
- Open **Assignments > Pin Planner**.
- Assign FPGA pins to your module’s inputs and outputs.
- Click **Save** once done.

### 7. Create Waveform for Simulation
- Go to **File > New > Other Files > Vector Waveform File (.vwf)**.
- Click **Edit > Insert > Insert Node or Bus**.
- Select all input and output signals to monitor.

### 8. Set Simulation Parameters
- Define end time using **Edit > End Time** (e.g., `1 us`).
- Apply different **input combinations** on the waveform.

### 9. Run Functional Simulation
- Go to **Processing > Start Simulation**.
- The **timing diagram** (simulation output) will be displayed.

### 10. Save the Timing Diagram
- Save the waveform for future reference.
- Export the timing diagram image via **File > Export Image**.

**PROGRAM**

![Screenshot 2025-05-14 221718](https://github.com/user-attachments/assets/42eee470-d6f5-4fae-8bda-9e7965f93337)


**RTL LOGIC FOR SISO Shift Register**

![Screenshot 2025-05-14 221729](https://github.com/user-attachments/assets/6414373f-f65f-4f5e-999a-a78f29272e76)


**TIMING DIGRAMS FOR SISO Shift Register**

![Screenshot 2025-05-14 221753](https://github.com/user-attachments/assets/6230b939-1ad8-48d2-903b-88698a0b2a1c)


**RESULTS**

Therefore the SISO Shift Register using verilog is implemented and their functionality using their functional tables is validated.
