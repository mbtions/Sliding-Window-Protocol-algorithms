# Sliding-Window-Protocol-algorithms

## What is Sliding Window Protocol ?

  A sliding window protocol is a feature of packet-based data transmission protocols. 
  Sliding window protocols are used where *reliable in-order delivery of packets* is required, 
  such as in the data link layer (OSI layer 2) as well as in the __Transmission Control Protocol (TCP)__.

## Types of Sliding Window Protocol
There are three types of Sliding Window Protocol :-
1. Stop and Wait ARQ
2. Go Back n ARQ
3. Selective Repeat ARQ

## What is Stop and Wait ARQ Protocol ?
In the transmission of duplex data transfer from the sender, receiver receives the data transmitted and sends the acknowledgement with the sequence number of next frame to be received. It is also known to have single bit sliding window as one bit is required to store the Sequence number, 0 and 1 are used to show the current and next frame.
