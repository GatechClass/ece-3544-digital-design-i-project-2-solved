# ece-3544-digital-design-i-project-2-solved
**TO GET THIS SOLUTION VISIT:** [ECE 3544: Digital Design I Project 2 Solved](https://mantutor.com/product/ece-3544-digital-design-i-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94334&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE 3544: Digital Design I Project 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Project 2: Modeling the Timing of a Device

Honor Code Requirements

Objectives

The purpose of this project is to use Verilog as a means for modelling the timing of a module. You will model an available component (the 74HC/HCT280 9-bit odd/even parity generator/checker) and use a delay model to analyze the timing of a system that utilizes the component.

Instructions

1. Study the clk and counter4bit modules. Simulate clk and counter4bit using the tb_clk and tb_counter modules.

I have provided Verilog models for a clock generator and a 4-bit synchronous counter. Study these two models to gain a good understanding of the behavior that they are meant to simulate. In particular, observe the manner in which each one uses parameters to establish default delays for their behavior in simulation. Please note that these modules have not been written with synthesizability in mind. In the particular case of the clock, the module cannot be used to generate a real clock signal, and we will not use it for that purpose. It is only meant to simulate the behavior of a clock in test benches.

I have also provided test benches for the clock generator and the counter. Study these test benches. Remember that test benches do not have their own ports. Instead, the test bench module generates stimulus values for the module you want to test. Use the test benches to simulate the clock and counter modules. Study the simulation results to further your understanding of how the clock generator and counter modules operate.

Among other things, the test benches will demonstrate the operation of the modules and the manner in which they should be connected within a system. The test benches also demonstrate the manner in which the designer can override a parameter when the module is instantiated. This technique is very useful, as it also works in situations where a synthesizable module is being instantiated in a higher-level module that we also intend to synthesize.

2. Use the 4-bit counter module as the basis for developing a 9-bit counter. Use the 9-bit counter’s test bench module as the basis for developing a test bench for your 9-bit counter.

Copy and modify the 4-bit counter module supplied with this project description. Name the new counter module counter9bit_YOURPID. Your 9-bit counter should have the same delay parameters as the 4-bit counter. Even though we have not yet formally studied synchronous counters, you should be able to infer the proper structure for your 9-bit counter from the 4-bit counter that I have given you. Remember that in a synchronous sequential, your procedural model should use a non-blocking assignment to target the counter’s state.

Use the test bench for the 4-bit counter as a model for making a test bench for the 9-bit counter. Name the test bench tb_counter9bit_YOURPID. In your report, include waveforms that demonstrate the correct behavior of your counter. You do not have to include the entire sequence of 11-bit counter states, but you should provide representative sections.

Develop and verify an untimed Verilog model for the 74HC/HCT280 9-bit odd/even parity

generator/checker. Develop a test bench for your circuit.

3.

Use the following module declaration for your circuit:

module hc280_YOURPID(data_in, even, odd); input [8:0] data_in;

output even, odd;

In each case where the specification provides the module declaration for a component, you must use that module declaration exactly as it appears. Failure to use the module declarations as provided will prevent the assignment graders from verifying the operation of your modules. If this happens, you will receive no credit for the affected portions of the project.

Write a test bench that uses the outputs of your 9-bit counter to drive the inputs of your parity circuit. Name your test bench tb_hc280_YOURPID. Your test bench should instantiate the clock generator, counter, and parity circuit models in a way that correctly connects their inputs and outputs together. Use the block diagram below as a model for structuring your test bench.

Figure 1: HC280 test-bench structure

To simulate your hc280 module with the counter module, your hc280 module must have a `timescale directive before the module declaration. Use the same directive as the 4-bit counter example: `timescale 1 ns/100 ps. The timescale directive tells the simulator that the value of one unit of time (#1) is 1 ns, and the precision (the smallest valid fraction of a time unit) is 100 ps.

In your report, include waveforms of inputs to and outputs from the untimed hc280 module that confirms its consistency with the function table on Page 4 of the datasheet. You do not have to include all combinations of the inputs on your waveforms, but you must show that your module behaves correctly for each line of the

function table.

Do not proceed to Step 4 until you have verified the correct operation of the untimed model.

4. Use a specify block to add propagation delays to your hc280 model.

Use the typical propagation delays at 25 degrees C and 4.5V from page 5 of the 74HC280 datasheet. You do not have to worry about the output transition time, only the propagation delays.

Simulate the timed model using your test bench. Your report should include waveforms showing the correct operation of the model with delays. You should also include waveforms with sufficient resolution to show that

the delays are correct.

5. Create a behavioral model of a 10-bit register.

Your register must have the following module declaration:

module register10bit_YOURPID(clk, d_in, q_out); input clk; input [9:0] d_in;

output [9:0] q_out;

This register should parallel load the values of d_in as the register state q_out on each rising edge of clk. The functionality of this module is essentially that of the 74FCT821 component described in the 74821 data sheet, but without the ability to tri-state the outputs. Your model of the 10-bit register should not include any delays.

Even though we have not yet formally studied synchronous registers, you should be able to infer the proper structure for your 10-bit register from information I have provided in lecture. Remember that in a synchronous sequential, your procedural model should use a non-blocking assignment to target the register’s state.

Create a test bench to verify the correct operation of your 10-bit register. Name the test bench

tb_register10bit_YOURPID. Your report should include a waveform showing its correct operation.

6. Use your models for the counter, the 74HC270, and the 10-bit register (74FCT821) to create the model of a digital system described below.

The channel is for 9 parallel data bits where the transmitter generates and sends an odd parity bit, and the receiver computes the odd parity of the data bits and compares the computed parity bit to the transmitted parity bit.

The schematic above describes two separate Verilog models.

transmit_YOURPID(clk, enable, clear, data_out); input clk, enable, clear; output [9:0] data_out;

The transmit module should contain an instance of your counter_9bit, hc280, and register_10bit modules. These are labeled as U1, U2, and U3 respectively. The counter_9bit should use the default propagation delay values that are in counter_4bit.

receive_YOURPID(clk, data_in, data_valid, data_out); input clk; input [9:0] data_in; output data_valid;

output [9:0] data_out;

The receive module should contain an instance of your register_10bit, hc20, and a parity bit comparator. These are labeled as U4, U5, and U6 respectively.

Finally, the overall schematic should be created in a tb_channelX() module, which should instantiate and connect the transmit and receive modules. You will replace X with a number that denotes the version number of the test bench, as described below. The test bench should also contain an instance of the clk module supplied with this project. Use a single clock to source all of the clocked elements. The clock and clock connections are not shown in the schematic for clarity.

You should create two versions of tb_channelX():

• The first version, tb_channel1(), should define the PERIOD parameter for clk that is sufficiently large to respect the propagation delays of the system. This should cause the data_valid signal shows the correct behavior at all times.

• The second version, tb_channel2(), should define the PERIOD parameter for clk that is small enough for the data_valid signal not to be asserted for some values of the receive module’s data_out.

For both versions of the test-bench, the delays in your 9-bit counter should be the default delays in the 4-bit counter.

Project Submission

Your project submission should include the following items:

1. A project report containing the following elements:

• A restatement of the assignment’s objectives.

• A discussion of the approach you took to modeling your modules, and a description of any design decisions you made as a part of implementing your modules.

• Waveforms that demonstrate the correct operation of each of the modules you create. Discuss how you formulated the tests contained in your test benches and how you verified the correctness of your implementation.

• An analysis of how you determined the PERIOD parameter of the clk module to demonstrate valid and invalid behavior of the system implemented in tb_channelX(). In particular, you should provide an analysis of the shortest clock period that will always allow correct (valid) behavior of the system.

• Waveforms that demonstrate valid and invalid behavior of the system.

• A discussion of your conclusions and the lessons you learned from the assignment.

Your report should be in PDF format. Include your PID in your report filename, e.g., project2report_jthweatt.pdf.

2. Source files for:

a. hc280 with delay implemented, and test bench

b. counter9bit, and test bench

c. register10bit, and test bench

d. transmit

e. receive

f. channel_tb1

g. channel_tb2

Remember to include your Virginia Tech PID in the names of your files. Submit your report and source as a single zip file on the project assignment page. Include your PID in the name of your archive file, e.g., project2files_jthweatt.zip.

Grading for your submission will be as described on the cover sheet included with this description. You must include the provided cover sheet as the first page of your report. I have provided it as a .doc so that you can make it the first page of your report prior to converting it into a PDF file.
