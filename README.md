Ring Counter is a sequential circuit It is a typical application of the Shift register. The ring counter is almost the same as the shift counter. The only change is that the output of the last flip-flop is connected to the input of the first flip-flop in the case of the ring counter but in the case of the shift register it is taken as output. Except for this, all the other things are the same.
No of states of Ring counter=No.of bits 
 I have designed a synchronous Ring counter using 2bit counter and 2x4 decoder using structural modelling where the sub modules are instantianted to build the top module. 
 For every posedge of the clock the output is taken out at last flipflop when the reset is high the output is low and when the reset is low the output is taken out. As it is a 4 bit ringcounter after 4 clock pulses we can see the output.
