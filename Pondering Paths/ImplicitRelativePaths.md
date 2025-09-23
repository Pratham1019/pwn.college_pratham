# Pondering Paths

## Implicit Relative Paths, from / 
The challenge asks to open the terminal and execute the /challenge/run program using relative paths. While executing the program, the cwd (current working directory) must be '/'. A hint has been provided that the relative path starts from the letter 'c'.

### Solve
**Flag:** `pwn.college{s11Qa9agRMWiEA8k-JPqqnj_vU_.QX5QTN0wCM0kDMzEzW}`

To solve this challenge, I first navigated to the root directory '/' since the current working directory needed to be set to the root. From there I executed the program 'challenge/run' instead of '/challenge/run' as the task required the usage of relative paths.

```bash
cd /
challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{s11Qa9agRMWiEA8k-JPqqnj_vU_.QX5QTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt the differences between absolute and relative paths inside a linux terminal and how the relative paths is relative to or dependent upon the cwd.
