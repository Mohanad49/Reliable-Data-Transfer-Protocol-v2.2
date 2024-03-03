# Reliable Data Transfer Protocol (RDTv2.2)

# Description
This project implements the Reliable Data Transfer Protocol version 2.2 (RDTv2.2) as a stop-and-wait protocol with positive acknowledgment and retransmission. The protocol uses an alternating bit approach with 1-bit sequence numbers and tolerates packet corruption.

# Features
- Stop-and-wait protocol implementation
- Positive acknowledgment with retransmission
- Alternating bit approach for packet sequence numbers
- Tolerance for packet corruption

# File Structure
- main.py: Main script to start and test the RDTv2.2 protocol.
- sender.py: Implementation of the RDTv2.2 sender side.
- receiver.py: Implementation of the RDTv2.2 receiver side.
- network.py: Implementation of the network layer for packet delivery and acknowledgments.
