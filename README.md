Analog Front-End PCB Design for Cyclic Voltammetry.
This project focuses on the design and development of an Analog Front-End current sensing circuit created for a Cyclic Voltammetry system. Developed during a research internship at the Sixth Sense Lab, IISER Bhopal, this board detects tiny electrical currents generated during chemical reactions and converts them into clear, measurable voltage signals for detailed analysis.  

Overview & Key FeaturesCore Function: 
1. Converts microampere-level currents produced during electrochemical reactions into readable voltage levels.
2. Amplifier Architecture: Utilizes an operational amplifier connected in a current-to-voltage conversion layout to ensure precise detection.
3. System Integration: Designed specifically to support three-electrode electrochemical testing setups for high-accuracy readings.
4. Hardware Connection: Uses simple pin header connectors for input signal lines, board power supply, and output measurement lines.
5. Board Layout: Optimized PCB layout designed in KiCad, featuring dedicated ground copper fills to block unwanted electrical noise and interference.

Bill of Materials Summary:
1. Operational Amplifier: Operational amplifier IC used as the core processing component.
2. Feedback Resistor: High-precision resistor that controls how much the input current is scaled into output voltage.
3. Connectors: Two-pin headers used to easily hook up input signals, power lines, and output connections.

Testing & Design Verification
Computer Simulation: Simulated using circuit software to ensure the board responds smoothly across the entire target current range before physical manufacturing.  
Design Rule Checks: Layout verified within KiCad to ensure trace widths and component clearances meet standard manufacturing requirements.  
Manufacturing Ready: Generated full production files (Gerber and drill files) ready for double-layer board fabrication.
