# Congestion Control Project

Made for the University of Cape Town (EEE4121F) by Shahil Poonsamy

This notebook investigates the performance of a network-assisted congestion control protocol against common TCP congestion control algorithms as an alternative to network emulation. This protocol is called TCP Tactile for the intents of this investigation, as it receives a 'physical sense' of the network. TCP Tactile includes a modified TCP header which contains aggregate router congestion information and other control features; however, only the congestion information contain in the data payload headers will be considered here (i.e. the network will not be considered to be sending any other messages besides application layer data, including handshaking and "slow-down" messages)
