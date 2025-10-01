# Comprehending Commands
## cat: not the pet, but the command!
In this challenge, I will copy the flag to the flag file in your home directory (where your shell starts). Go read it with cat!

Solve
Flag: pwn.college{EIY7w5EYbNlikJJrPtGFjL711Cw.QXxcTN0wiNzAzNzEzW}
```bash
cat flag
```
In this challenge, I typed cat flag command to get the flag.

Learned about cat command and how it works.
## Catting absolute paths
In this directory, I will not copy it to your home directory, but I will make it readable. You can read it with cat at its absolute path: /flag.

Solve

<img width="570" height="118" alt="Screenshot 2025-09-24 181929" src="https://github.com/user-attachments/assets/b1e3f89c-f8c9-4900-a813-52890c835171" />


Learned about invoking cat command using absolute paths.

## More catting practice

In this level, I'll put the flag in some crazy directory, and I will not allow you to change directories with cd, so no cat flag for you. You must retrieve the flag by absolute path, wherever it is.

Solve

<img width="895" height="327" alt="Screenshot 2025-09-24 183039" src="https://github.com/user-attachments/assets/3abdf445-a67d-4129-a3e0-612a0428bad8" />

Practiced more catting commands.

## grepping for a needle in a haystack

In this challenge, I've put a hundred thousand lines of text into the /challenge/data.txt file. grep it for the flag!

Solve

<img width="1448" height="270" alt="Screenshot 2025-09-24 183545" src="https://github.com/user-attachments/assets/6ae612b3-7f87-4d3b-8aa9-dfaaf887131f" />

Learned about grep command and how to use it.

## comparing files

Now for your challenge! There are two files in /challenge:

/challenge/decoys_only.txt contains 100 fake flags /challenge/decoys_and_real.txt contains all 100 fake flags plus the one real flag Use diff to find what's different between these files and get your flag!

Solve

<img width="1014" height="367" alt="Screenshot 2025-09-24 184208" src="https://github.com/user-attachments/assets/f94d018b-99b1-4ab1-a833-4e2e58177046" />

Learned about diff command and how it can be used to compare two files line by line.

## listing files
In this challenge, we've named /challenge/run with some random name! List the files in /challenge to find it.

Solve

<img width="1449" height="527" alt="Screenshot 2025-09-24 184713" src="https://github.com/user-attachments/assets/ed7ce6c1-535a-4802-a46c-81595bb97ff9" />

Learned about using ls command and how it works.

## touching files
In this level, please create two files: /tmp/pwn and /tmp/college, and run /challenge/run to get your flag!

Solve

<img width="888" height="280" alt="Screenshot 2025-09-24 190614" src="https://github.com/user-attachments/assets/7a7375b0-599e-462e-af88-0606f3e551f2" />

Learned about creating new files using touch command.

## removing files
This challenge will create a delete_me file in your home directory! Delete it, then run /challenge/check, which will make sure you've deleted it and then give you the flag!

Solve

<img width="777" height="228" alt="Screenshot 2025-09-24 191237" src="https://github.com/user-attachments/assets/7ebd7ee9-be39-44cd-94f6-6076e3ff3856" />

Learned about removing files using rm command.

## moving files

moving files
This challenge wants you to move the /flag file into /tmp/hack-the-planet (do it)! When you're done, run /challenge/check, which will check things out and give the flag to you.

Solve

<img width="1300" height="523" alt="Screenshot 2025-09-24 192234" src="https://github.com/user-attachments/assets/8e506e9c-acca-4b61-965f-53b470754f73" />

Learned about moving files using mv command.

## hidden files

Go find the flag, hidden as a dot-prepended file in /.

Solve

<img width="1167" height="511" alt="Screenshot 2025-09-24 193444" src="https://github.com/user-attachments/assets/3d9898f6-70fb-412d-81bc-934245dcde9f" />

Learned about reading and accessing hidden files using -a command.

## An Epic Filesystem Quest
In this challenge, I have hidden the flag! Here, you will use ls and cat to follow my breadcrumbs and find it! Here's how it'll work:

Your first clue is in /. Head on over there. Look around with ls. There'll be a file named HINT or CLUE or something along those lines! cat that file to read the clue! Depending on what the clue says, 

head on over to the next directory (or don't!). Follow the clues to the flag!

Solve

<img width="1901" height="443" alt="Screenshot 2025-09-29 023209" src="https://github.com/user-attachments/assets/7d80bb6b-a99e-45b5-b25a-ae026c3acdbe" />

Learned how I can follow around clues or hints to eventually get the flag.

## making directories
Now, go forth and create a /tmp/pwn directory and make a college file in it! Then run /challenge/run, which will check your solution and give you the flag!

Solve

<img width="1800" height="521" alt="Screenshot 2025-09-25 000055" src="https://github.com/user-attachments/assets/9b16778c-a85e-4751-8809-31a06b0dc9c7" />

Learned about making directories using mkdir command.

## finding files
Now it's your turn. I've hidden the flag in a random directory on the filesystem. It's still called flag. Go find it!

Several notes. First, there are other files named flag on the filesystem. Don't panic if the first one you try doesn't have the actual flag in it. Second, there're plenty of places in the filesystem
that are not accessible to a normal user. These will cause find to generate errors, but you can ignore those; we won't hide the flag there! Finally, find can take a while; be patient!

Solve
 
<img width="1266" height="287" alt="Screenshot 2025-09-26 175126" src="https://github.com/user-attachments/assets/60858b69-2069-4d7b-8a50-b7a945e21329" />

Learned about finding files using a specific name as argument.

## linking files

In this level the flag is, as always, in /flag, but /challenge/catflag will instead read out /home/hacker/not-the-flag. Use the symlink, and fool it into giving you the flag!

Solve

<img width="843" height="403" alt="Screenshot 2025-09-26 180244" src="https://github.com/user-attachments/assets/d8fe1203-0631-4ca8-bbb6-d37335b0f233" />

Learned about linking and its two types hard and symbolic link.

