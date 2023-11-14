In the following file after going through it we see that the user_buf is vulnerable. This is because we can use format specifier in the input which will prompt it to print all the value that the stack has. %x will return hex values from the stack which can help us to identify the flag.
<img width="487" alt="Screenshot 2023-11-15 at 12 43 14 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/4661e630-e270-4424-81d5-50e6495415b2">
By flooding it with %x we get the hex values.
<img width="565" alt="Screenshot 2023-11-15 at 12 45 31 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/b3cfd187-9fe0-4246-8612-657634f5e247">
After converting the hex value to ascii we get the flag however it seems to be in some reverse order. After looking it up it is in little endian. We can convert this back to big endian through an online compiler and get the flag
<img width="565" alt="Screenshot 2023-11-15 at 12 45 41 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/31cadbf7-ddfc-4082-bbff-392d84e8826c">
