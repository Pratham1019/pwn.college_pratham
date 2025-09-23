# Pondering Paths

## Position Yet Elsewhere
The challenge asks you to open the terminal then change your current directory to the specified one and then execute the /challenge/run program from there to get the flag.

### Solve
**Flag:** `pwn.college{0App0CI9Wz70kP49OAXa5HcJ1KO.QX4QTN0wCM0kDMzEzW}`

For solving this challenge, I first tried to execute the program /challenge/run from the home directory but this resulted in an error.

```bash
/challenge/run
Incorrect...
You are not currently in the /proc/131 directory.
Please use the `cd` utility to change directory appropriately.
```

After seeing the error I navigated to the /proc/131 directory using the cd command and then executed the /challenge/run program, which successfully returned the flag.

```bash
cd /proc/131
/challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{0App0CI9Wz70kP49OAXa5HcJ1KO.QX4QTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt how to use the cd commnand to navigate to other directories. 
