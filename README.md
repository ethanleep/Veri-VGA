# Veri-VGA
A small 640 x 480 Verilog timing module

The module itself has one input for a 25.125MHz clock and 4 outputs for the vertical address, horizontal address, and sync signals. Only the sync signals should be passed to the actual VGA connector while the address vectors are for determining which pixel to output in your own code.
