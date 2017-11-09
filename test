//IEEE Floating Point Adder (Single Precision) Test Bench
`include "VerilogBM_120-120.v"
`timescale 1ns/1ns
module Verilog_120_120120();
reg input_a,input_b,clk,rst;
wire output_z; 
initial
begin
$dumpfile("VerilogBM_120_120_add.vcd");
$dumpvars(0,Verilog_120_120);
end
adder adder_Verilog_120_120(input_a,input_b,clk,rst,output_z);
initial begin
forever begin
C=0;
#1 C=1;
#1 C=0;
end
end
initial
begin
input_a=00000000000000000000000000000000; 
input_b=00000000000000000000000000000000; 
#1 input_a=01000001110010000000000000000000; 
input_b=01000001001000000000000000000000;
end
endmodule
module Verilog_120_120120();
reg input_a,input_b,clk,rst;
wire output_z; 
initial
begin
$dumpfile("VerilogBM_120_120_div.vcd");
$dumpvars(0,Verilog_120_120);
end
divider divider_Verilog_120_120(input_a,input_b,clk,rst,output_z);
initial begin
forever begin
C=0;
#1 C=1;
#1 C=0;
end
end
initial
begin
input_a=00000000000000000000000000000000; 
input_b=00000000000000000000000000000000; 
#1 input_a=01000001110010000000000000000000; 
input_b=01000001001000000000000000000000;
end
initial
begin
$monitor("input_a=%32b input_b=%32b output_z=%32b clk=%1b",input_a,input_b,output_z,clk); 
end
endmodule
module Verilog_120_120120();
reg input_a,input_b,clk,rst;
wire output_z; 
initial
begin
$dumpfile("VerilogBM_120_120.vcd");
$dumpvars(0,Verilog_120_120);
end
multiplier multiplier_Verilog_120_120(input_a,input_b,clk,rst,output_z);
initial
begin
$dumpfile("VerilogBM_120_120_mult.vcd");
$dumpvars(0,Verilog_120_120);
end
initial begin
forever begin
C=0;
#1 C=1;
#1 C=0;
end
end
initial
begin
input_a=00000000000000000000000000000000; 
input_b=00000000000000000000000000000000; 
#1 input_a=01000001110010000000000000000000; 
input_b=01000001001000000000000000000000;
end
initial
begin
$monitor("input_a=%32b input_b=%32b output_z=%32b clk=%1b",input_a,input_b,output_z,clk); 
end
endmodule

