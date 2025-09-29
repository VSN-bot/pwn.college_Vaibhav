# Pondering Paths
## The root
You can invoke a program by providing its path on the command line. In this case, you'll be giving the exact path, starting from /, so the path would be /pwn. This style of path, one that starts with the root 
directory, is referred to as an "absolute path".

Solve
Flag: pwn.college{Ay2_xmsN6DclRauxb4rIbLnBOGd.QX4cTO0wiNzAzNzEzW}

In this challenge, I invoked pwn command using its absolute path from / to get the flag.
Learnt to write path of programs using '/'. we write the file or program name after the forward slash.
## Program and absolute paths
This challenge again requires you to execute it by invoking its absolute path. You'll want to execute the run file that is in the challenge directory that is, in turn, in the / directory.
If you invoke the challenge correctly, it will give you the flag.

Solve
Flag: pwn.college{0gJRIPz6PcFR2JJYVH8svdTN6Ix.QX1QTN0wiNzAzNzEzW}

In this challenge, I typed /challenge/run using absolute path to get the flag.
Learned how to invoke slightly more complicated paths.

## Position thy self
This challenge will require you to execute the /challenge/run program from a specific path (which it will tell you).

Solve
Flag: pwn.college{0CjgiU10osplI9mtzx96nH6zlHqj.QX2QTN0woNwIzNzEzW}

first entered /challenge/run, then it showed that I'm not in the /usr/share/build-essential directory. So that is the path where I'm supposed to run the /challenge/run program.
Learnt to enter a specific path, i.e. change the current directory using cd and run the required program
## Position elsewhere
This challenge will require you to execute the /challenge/run program from a specific path (which it will tell you). You'll need to cd to that directory before rerunning the challenge program.

Solve
Flag: pwn.college{AQt6GkenayeP8jns_Fb4iisKOkP.QX3QTN0wiNzAzNzEzW}

In this challenge, Firstly, I ran the /challenge/run command to know which path the flag is in. Then, I used cd /var/log to switch current working directory and ran the challenge command again to get the flag.
Learned how to change directory and invoking absolute paths from there.

## Position yet elsewhere
To run the /challenge/run program in a specific path

Solve
Flag: pwn.college{Y7RA3MncztjYsIHyiu5IJVBS6h5.QX4QTN0wiNwIzNzEzW}

first entered /challenge/run, then it showed that I'm not in the /usr/share/doc directory. So that is the path where I'm supposed to run the /challenge/run program.
Learnt to enter a specific path, i.e. change the current directory using cd and run the required program

## Implicit relative paths, from /
This challenge will get you using . in your relative paths.
Solve
Flag: pwn.college{osZ-2uT1GtUv16s8lgK_yKY6AP2.QX5QTN0wiNzAzNzEzW}
Learned how to invoke commands using implicit relative paths.

## Explicit relative paths form /
To run challenge/run explicitly using '.'

Solve
Flag: pwn.college{UJOBHYv54mPFnZZYEQBXHZUHEPm.QXwUTN0wiNwIzNzEzW}

Using ./ in front of the program to run, gives a relative path to the same program
To run a program using explicit relative path.

## Implicit relative path
To implicitly run a fuctiion from a directory without the /

Solve
Flag: pwn.college{wD_5sx5_eDpZI4e0BUArNpnz9Zs.QXxUTN0wiNwIzNzEzW}

Entered the challenge directory using /challenge and had to call the run program implicitly so used, ./ because it invokes the same program.
To invoke a program using implicit relative path from a directory, bypassing the bash's explicit overview of '/'.
## Home sweet home

In this challenge, /challenge/run will write a copy of the flag to any file you specify as an argument on the commandline, with these constraints:

Your argument must be an absolute path. The path must be inside your home directory. Before expansion, your argument must be three characters or less. Again, you must specify your path as an argument to /challenge/run.

Solve
Flag: pwn.college{sV4GGnyUt_XkZLCfq3qfCkeEeBT.QXzMDO0wiNzAzNzEzW}

In this challenge, At first, I used /challenge/run command with argument as ~ which didn't return any flag. Then, I used ~/~ as argument and got the flag.

