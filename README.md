# 4BIT_SYNCHRONOUS_UP_COUNTER
![image](https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/4d676d34-2f12-420a-9c55-befa279f5ec0)
# Truth Table
# <img width="362" alt="image" src="https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/2be84c5a-099f-4418-8d0b-ace34f734342">
# Timing diagram of the synchronous counter
![image](https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/62c47758-b0a4-4fe0-842f-5c4245a88ff2)

VERILOG CODE
`````````````````````````````````````
module synchronous_up_counter(
input wire clk, 
input wire reset, 
output reg [3:0] count // 4-bit output );
always @(posedge clk or posedge reset)
begin
if (reset)
count <= 4'b0000;
else
count <= count + 1; 
end
endmodule
``````````````````````````````````````````
OUTPUT

![Uploading image.png…]()





