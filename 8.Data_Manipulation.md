# Data Manipulation
## Deleting characters
I'll intersperse some decoy characters (specifically: ^ and %) among the flag characters. Use tr -d to remove them!

Solve

<img width="1082" height="251" alt="Screenshot 2025-09-27 235024" src="https://github.com/user-attachments/assets/c1ec918a-c5e0-4b19-8650-366853e08e62" />

Learned about deleting characters.

## Translating characters
In this level, /challenge/run will print the flag but will swap the casing of all characters (e.g., A will become a and vice-versa). Can you undo it with tr and get the flag?

Solve

<img width="1782" height="459" alt="Screenshot 2025-09-27 234315" src="https://github.com/user-attachments/assets/cb6d112d-6eb9-43ef-8c4f-c6025b46ca6e" />

Learned about translating characters.

## Deleting characters

I'll intersperse some decoy characters (specifically: ^ and %) among the flag characters. Use tr -d to remove them!

Solve

<img width="1082" height="251" alt="Screenshot 2025-09-27 235024" src="https://github.com/user-attachments/assets/50d235a5-e897-4c1e-9c98-c4e25b9eee07" />

Learned about deleting characters.

## Deleting newlines
Now, let's combine this with deletion. In this challenge, we'll inject a bunch of newlines into the flag. Delete them with tr's -d flag and the escaped newline specification!

Solve

<img width="1525" height="248" alt="Screenshot 2025-09-28 184534" src="https://github.com/user-attachments/assets/b56739d3-205c-4393-94ee-47fa2a0e48c7" />

Learned about deleting newlines.

## Extracting specific sections of text
In this challenge, the /challenge/run program will give you a bunch of lines with random numbers and single characters (characters of the flag) as columns. Use cut to extract the flag characters, then pipe them to tr -d "\n" (like the previous level!) to join them together into a single line. Your solution will look something like /challenge/run | cut ??? | tr ???, with the ??? filled out.

Solve

<img width="1497" height="330" alt="Screenshot 2025-09-28 191842" src="https://github.com/user-attachments/assets/0b6e8399-9c96-4c67-8f01-fc29542bd85e" />

Learned about extracting specific columns of text.

