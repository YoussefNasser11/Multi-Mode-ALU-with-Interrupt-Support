# Multi-Mode-ALU-with-Interrupt-Support - Class based testbench
Key Features:

Dual Modes: The ALU operates in two distinct modes, Mode A and Mode B, providing flexibility for various computation tasks.
Interrupt Support: An interrupt signal is triggered when specific values appear on the output, enhancing real-time event handling and responsiveness.
Interrupt Clear Signal: To streamline control, the ALU includes a clear signal for deasserting the interrupt request, ensuring efficient handling of interrupt events.
Forbidden Values: The ALU incorporates safety measures by restricting certain values from computation.

Verification Environment:
As part of this project, I meticulously developed a comprehensive Verification Environment, leveraging advanced methodologies for thorough testing:

Testbench: Designed a robust testbench to thoroughly validate the ALU's functionality in diverse scenarios.
Configuration Class: Implemented a flexible configuration class to easily customize the ALU's parameters and behavior during testing.
Environment Class: Created an environment class to orchestrate the simulation and manage all verification components seamlessly.
Driver-Monitor Classes: Developed specialized driver and monitor classes to facilitate efficient data transfer between the testbench and the ALU.
Sequencer: Designed a sequencer to control the flow of transactions, ensuring a systematic approach to testing scenarios.
Transaction Class: Defined a transaction class to represent data transfers between the testbench and the ALU, promoting clarity and modularity.
Scoreboard: Implemented a scoreboard to validate the correctness of ALU outputs against expected results, enhancing verification accuracy.
Subscriber Class: Integrated a subscriber class to capture and analyze key events during simulation, aiding in debugging and verification result analysis.


Results and Validation:
I rigorously tested the ALU using a well-defined verification plan, and the results were validated using Verdi, Synopsys's advanced simulation tool.
