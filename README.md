# Hi, I'm Aatif Junaid

Final-year B.Tech ECE student at Netaji Subhas University of Technology (NSUT), targeting processor design and verification. I work in RTL design, pipelined processor architecture, constrained-random verification, SVA and functional coverage.

## Projects

### 5-Stage Pipelined RISC-V (RV32I) Core | Verilog, SystemVerilog, SVA
- Designed a 5-stage pipelined core supporting 8 instructions, with data forwarding, a 1-cycle load-use stall and a 2-instruction branch flush.
- Verified with a self-checking testbench running 5 assembly programs against a single-cycle reference model, comparing all 32 registers and 256 memory words (5/5 passing).
- Added 4 SVA assertions (x0 = 0, stall only on load-use, flush only on taken branch, bubble insertion).

### Synchronous FIFO Verification | SystemVerilog, SVA, Functional Coverage, Cadence Xcelium
- Developed a class-based, self-checking testbench (constrained-random generator, driver, monitor, queue-based scoreboard) for a parameterized synchronous FIFO.
- Implemented 17 bound SVA assertions and 4 covergroups with a coverage-closure loop, reaching 100% functional coverage with 0 scoreboard errors and 0 assertion failures.
- Injected all 10 deliberate RTL bugs and confirmed the testbench caught each one.

### UART Transmitter | Verilog HDL, FSM, RTL Design, Yosys
- Designed an FSM-based UART transmitter (IDLE/START/DATA/STOP) with a shift register and a parameterized baud rate (100 MHz clock → 9600 baud).
- Verified with a self-checking testbench using a behavioral receiver model as monitor/checker (15 tests, all passing).
- Synthesized with Yosys to a gate-level netlist (171 cells, 34 flip-flops) and documented the results in the repo.

### Blind Assistance Wearable Device | Arduino, C++, Ultrasonic Sensors
- Built a wearable obstacle and elevation-change detector on Arduino Uno using 2 ultrasonic sensors, alerting for obstacles within 80 cm and for raised surfaces or drops.
- Implemented priority-based alert logic with 5 distinct buzzer patterns, including a timeout fallback for sensor failures.
- Worked in a 3-member team on hardware integration, testing and enclosure prototyping.

### Other Projects
- **ChargeNow:** a smart EV slot finder for the Indian market (Python, Flask, SQLite, Leaflet.js).
- **WhatsApp Sentiment Analyzer:** chat analytics dashboard (Python, Scikit-learn, Hugging Face, Streamlit).
- **PDF Summarizer with Q&A:** built at NTPC (Python, NLP, FLAN-T5).

## Technical Skills
- **HDL & Verification:** Verilog HDL, SystemVerilog, SVA, constrained-random verification, functional coverage, self-checking testbenches
- **Languages:** Python, C++, C, Tcl
- **Embedded:** Arduino, Microcontrollers, Sensor Integration
- **Tools:** Cadence Xcelium & Icarus Verilog (EDA Playground), Yosys, Git, GitHub, MATLAB, LTSpice

## Internships
- **BHEL, Noida** (Jun–Jul 2026)
- **NTPC Limited, Noida** (Jun–Jul 2025)
