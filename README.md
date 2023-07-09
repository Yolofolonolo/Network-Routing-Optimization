# Network-Routing-Optimization
Enhanced Routing and Performance Analysis in Computer Networks
This project focuses on implementing a Link State Routing (LSR) protocol, analyzing TCP performance, and exploring different server designs. The goal is to enhance network routing efficiency, optimize TCP performance, and improve server responsiveness.

Project Structure
The project is organized into the following sections:

LSR Protocol Implementation:

The existing Distance Vector Routing (DVR) algorithm (Routing Information Protocol - RIP) implementation is modified to create a functionally correct LSR implementation.
Changes to data structures, routing algorithms, and routing table update mechanisms are made.
Simulations are run with varied parameters to validate and analyze the LSR implementation.
TCP Performance Analysis:

Average TCP throughput at the receiver is calculated by analyzing pcap files using tools such as Wireshark and tshark.
The evolution of the sender's congestion window (cwnd) over time is plotted using graph plotting software like gnuplot.
Queue length and queueing delay at the sender's buffer are analyzed by processing trace files obtained from simulations.
Server Designs:

Different server designs are implemented, including sequential, concurrent (with multiple processes and threads), and non-blocking (using select(), poll(), and epoll API) server programs.
Metrics such as response time, CPU utilization, and memory utilization are measured to evaluate the performance of each server design.
Tools and Technologies Used
Programming Language: C
Network Simulator: ns-3
Packet Analysis: Wireshark, tshark
Graph Plotting: gnuplot
Command Line Tools: sed, awk, perl, python
Operating System: Linux
Text Editing: Any preferred text editor (e.g., Vim, Sublime Text)
Version Control: Git
Documentation: LaTeX or Microsoft Word
Usage
LSR Protocol Implementation:

Refer to the implementation files and make necessary modifications to the existing DVR algorithm.
Run simulations using the provided parameters and analyze the output files.
TCP Performance Analysis:

Use Wireshark or tshark to extract relevant information from pcap files and calculate average throughput.
Plot the cwnd values over time using gnuplot or any graph plotting software.
Analyze trace files to obtain queue length and queueing delay information.
Server Designs:

Implement the server programs according to the desired design (sequential, concurrent, or non-blocking).
Measure relevant metrics such as response time, CPU utilization, and memory utilization.
