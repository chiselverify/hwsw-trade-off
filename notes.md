
# Collection of Notes

Besides our use cases of sorting and path-finding, we could add some more:

 * Use Bosse's CNN coprocessor
 * Game of Life is very HW friendly ;-)

We can compare between HW in the FPGA and Patmos in the FPGA. However,
this may be unfair, as FPGAs are not efficient for processors.
We better use some embedded processor for comparison.
Another option is to use an FPGA with a hard code. Then those two
approaches are in the same technology, but the processor has
not the overhead of FPGA programmability. Furthermore, this
allows that the HW and SW solution have the same overhead of
mamory access. A nice (and cheap) board is the DE10-nano that
conatins an Arm. We have several at DTU to play with.
