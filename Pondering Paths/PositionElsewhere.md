# Pondering Paths

## Position Elsewhere
The challenge asks you to open the terminal then change your current directory to the specified one and then execute the /challenge/run program from there to get the flag.

### Solve
**Flag:** `pwn.college{EvKe0ahDisJQqyCffx31Xk-6aAO.QX3QTN0wCM0kDMzEzW}`

For solving this challenge, I first tried to execute the program /challenge/run from the home directory but this resulted in an error.

```bash
/challenge/run
Incorrect...
You are not currently in the /etc directory.
Please use the `cd` utility to change directory appropriately.
```

After seeing the error I navigated to the /etc directory using the cd command and then executed the /challenge/run program, which successfully returned the flag.

```bash
cd /etc
/challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{EvKe0ahDisJQqyCffx31Xk-6aAO.QX3QTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt how to use the cd commnand to navigate to other directories. 
