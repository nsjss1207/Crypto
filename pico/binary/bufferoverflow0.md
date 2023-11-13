Buffer Overflow 0

In the following CTF after doing a bit of research I found that the gets function is prone to buffer overflow. If we exceed the storage capacity
of gets it will overflow into different memory location. The SIGSEGV (Segmentation function) checks if there is any overflow beyond the bounds.
If we input a large number of characters and press enter it causes buffer overflow and we get the value of the flag.
<img width="733" alt="Screenshot 2023-11-14 at 1 40 18 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/90363392-850b-4145-9d81-e4c9129599ad">
