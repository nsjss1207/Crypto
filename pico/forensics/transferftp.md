First we install wireshark which is an open-source software which helps to capture the data travelling back and forth to the network. We then export the data as tftp on our computers. The following files are exported. 
<img width="758" alt="Screenshot 2023-11-14 at 11 48 02 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/7d1bf6e5-be4f-4466-9cb3-2c4bb26a65df">

We then use the ls command to list these files in terminal and to read them we use the cat command.
<img width="559" alt="Screenshot 2023-11-14 at 11 47 44 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/c4917b30-cf23-4c31-8b0f-2a143b72c111">

These files look to be encoded by rot13. After passing through a decoder online the plan file prints out the following message:

<img width="487" alt="Screenshot 2023-11-14 at 11 49 49 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/9ea4fd2d-ecdf-4f62-8c41-c098a1df0bf7">

I have also read that data in images can be concealed by steganography. I then opened an online steganography decoder and started to pass the images one-by-one using DUEDILIGENCE as the password. Image 3 hid the flag.
<img width="487" alt="Screenshot 2023-11-14 at 11 52 25 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/8c267005-7315-42b9-a37a-7542ac4e59ae">
<img width="487" alt="Screenshot 2023-11-14 at 11 52 17 AM" src="https://github.com/nsjss1207/Crypto/assets/107710230/02faf048-1dba-4566-a3f3-eca5da208cb2">

