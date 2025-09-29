# Perceiving Permission

## Changing File Ownership
In this level, we will practice changing the owner of the /flag file to the hacker user, and then read the flag. For this challenge only, I made it so that you can use chown to your heart's content as the hacker user (again, typically, this requires you to be root). Use this power wisely and chown away!

Solve

<img width="1331" height="293" alt="Screenshot 2025-09-29 130136" src="https://github.com/user-attachments/assets/d9fdf7ff-8b86-4677-939f-96ac2e0f1bf2" />

Learned about changing file ownerships.

## Groups and Files
In this level, I have made the flag readable by whatever group owns it, but this group is currently root. Luckily, I have also made it possible for you to invoke chgrp as the hacker user! Change the group ownership of the flag file, and read the flag!

Solve

<img width="1246" height="385" alt="Screenshot 2025-09-29 131124" src="https://github.com/user-attachments/assets/83b93457-5bd1-47bf-8ad1-72e592e9ef65" />

Learned about changing groups and files ownerships.

## Fun With Groups Names
The point is, you've used hacker for the group before, but in this level, that is not going to work. I'll still allow you to use chgrp, but I have randomized the name of the group that your user is in. You will need to use the id command to figure that name out, then chgrp to victory!

Solve

<img width="1361" height="199" alt="Screenshot 2025-09-29 131605" src="https://github.com/user-attachments/assets/b1651af1-2e61-48f0-9664-7a506c452fa8" />

Learned about changing groups and files ownerships.

## Changing Permissions
In this challenge, you must change the permissions of the /flag file to read it! Typically, you need to have write access to the file in order to change its permissions.

Solve

<img width="1156" height="478" alt="Screenshot 2025-09-29 172658" src="https://github.com/user-attachments/assets/c55b6911-6eeb-48ee-8cd2-d07fd7254cbe" />

Learned about changing file permissions.

## Executable Files
In this challenge, the /challenge/run program will give you the flag, but you must first make it executable!

Solve

<img width="1342" height="405" alt="Screenshot 2025-09-29 174037" src="https://github.com/user-attachments/assets/5257f70e-e18f-4cc1-b1d3-37eb62200478" />

Learned about changing file permissions.

## Permission Tweaking Practice
This challenge will ask you to change the permissions of the /challenge/pwn file in specific ways a few times in a row. If you get the permissions wrong, the game will reset and you can try again. If you get the 

permissions right eight times in a row, the challenge will let you chmod /flag to make it readable for yourself :-) Launch /challenge/run to get started!

Solve

<img width="1437" height="345" alt="Screenshot 2025-09-29 180954" src="https://github.com/user-attachments/assets/b2b67308-99f1-4abc-9ab7-ed992c4123d7" />

Practiced permission tweaking.

## Permission Setting Practice
This level extends the previous level by requesting more radical permission changes, which you will need = and ,-chaining to achieve. Good luck!

Solve

<img width="1445" height="573" alt="Screenshot 2025-09-29 182333" src="https://github.com/user-attachments/assets/f590cc16-8882-46c0-8555-fc2b8b1c1b4d" />

Practiced permission setting.

## The SUID Bit
Now, we are going to let you add the SUID bit to the /challenge/getroot program in order to spawn a root shell for you to cat the flag yourself!

Solve

<img width="1019" height="158" alt="Screenshot 2025-09-29 182941" src="https://github.com/user-attachments/assets/bb415d49-6bcb-4349-ba61-2cc3404ecd09" />

Learned about SUID bit.

