Local Authority

After inspecting the html code of the website I found that the file was being directed to login.php. 
After directing to login.php and inspecting i found that there is a secure.js file. 
I found the password after reading secure.js file in the sources section.

CAAS

In this following CTF, I first read about how a person could attack a website. I found that injection attacks are common in webistes that accept inout from users.
Using that information I came across command injections in which linux commands can be passed with the given coomand on the page. 

<img width="230" alt="Screenshot 2023-11-10 at 9 13 53 PM" src="https://github.com/nsjss1207/Crypto/assets/107710230/8297d1c5-4e47-4ff3-9b52-7caa82599e26">


After running the ls command several files were displayed on the screen. Using the cat command with the falg.txt file I found the password.

Forbidden Paths

In this flag as the website is filtering out absolute paths, I searched to find a way through that.
I came across relative paths which can use the path relative to the current directory. 
By using relative paths by using the .. command be can be used to access the next directory. By replacing the absolute path usr/share/nginx/html/
with ../../../../flag.txt we get the flag.
