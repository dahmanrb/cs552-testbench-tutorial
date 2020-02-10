# CS 552 Verilog Testbench Tutorial
This document will detail all of the steps of writing and simulating a testbench in Modelsim. This assumes that you have already completed the Modelsim setup tutorial, [which can be found here](https://github.com/kyle-p-may/cs552-modelsim-tutorial).

## Creating a testbench
We have provided a 2-to-4 line binary decoder (decoder24.v), but we are not sure if it works correctly. To test the module, we'll create a testbench that lets us drive all combinations of the inputs to the module, and see what it outputs.

### Writing the testbench:
Create a new file in this directory, called `tb_decoder24.v`. As with all other Verilog designs, we will start by creating a new module and giving it a name.


