# Tiny Benchmark

This is a simple and stupid benchmark I wrote for funsies. 
Pure compute, no disk, no GPU. 
It's written in Python so that anyone can run it without downloading a complex program like geekbench.
This is in no way scientific. I just wanted something simple to run everywhere.

Run using Python 3.11.  
(This is important, results vary wildly across Python versions in my testing) 

Create a PR to add your results below.

It would be fun to see how you laptops, desktops, home labs, and even your phones with Termux stacks up.

# Results

At some point, this should be turned into a CSV. But this should do for now.

- Pi4 (8GB/4c/4t):  
  Single-threaded: 36.4213 seconds  
  Multi-process: 9.1086 seconds  

- N2840 (4GB/2c/2t):  
  Single-threaded: 39.1398 seconds  
  Multi-process: 20.0263 seconds  

- Snapdragon 7c (8GB/2P+6E/8t):  
  Single-threaded: 15.1639 seconds  
  Multi-process: 6.2345 seconds  

- Netcup (8GB/4vCPU/VPS 1000 G11):  
  Single-threaded: 13.6997 seconds  
  Multi-process: 3.4937 seconds  

- DigitalOcean (2GB/2vCPU/Premium AMD):  
  Single-threaded: 11.0227 seconds  
  Multi-process: 4.8285 seconds  

- M3 Air (16GB/4P+4E/8T)
  Single-threaded: 5.2768 seconds
  Multi-process: 1.1537 seconds

- M1 Pro (16GB/4P+4E/8T)
  Single-threaded: 7.9802 seconds
  Multi-process: 1.5595 seconds

- 5900HS (40GB/8c/16t):  
  Single-threaded: 7.3729 seconds  
  Multi-process: 1.3195 seconds  

