# Pondering Paths

## Home Sweet Home
The challenge asks to run '/challenge/run' with an argument that is an absolute path inside the home directory aand is 3 or less characters long.

### Solve
**Flag:** `pwn.college{InFvnlAclq18H-nxAzyUy_Rq2OP.QXzMDO0wCM0kDMzEzW}`

For solving this challenge I used '~' which is a shortform representation used by Bash as it's used again and again. The expanded form  of ~ is /home/hacker in this case. I ran the following command (/challenge/run ~/f) which successfully copied the flag to the file named f inside the home directory. Reading the file using the cat command successfully returned the flag.

```bash
/challenge/run ~/f
cat f
pwn.college{InFvnlAclq18H-nxAzyUy_Rq2OP.QXzMDO0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt that '~' are used as a shortform for the home directory in the linux terminal. Its expanded form in this case is /home/hacker which is an absolute path.