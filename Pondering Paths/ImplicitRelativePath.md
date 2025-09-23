# Pondering Paths

## Implicit Relative Path 
The challenge asks you to navigate into the '/challenge' directory and run the 'run' program, but instead of just typing run you must explicitly use './run' to tell Linux to execute the program from the current directory and not some system command.

### Solve
**Flag:** `pwn.college{Av-WGDiHlCmRKiAtn_UAXQQUkMQ.QXxUTN0wCM0kDMzEzW}`

To solve this challenge, I first navigated to the challenge directory '/challenge' and after that executed the 'run' program using './run' command which successfully returned the flag.

```bash
cd /challenge
./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{Av-WGDiHlCmRKiAtn_UAXQQUkMQ.QXxUTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt that its required to explicitly use './' in relative paths to execute programs inside of the cwd. This prevents conflicts with system programs which have the same name as the local programs inside of the cwd. 