# Pondering Paths

## Explicit Relative Paths, from / 
The challenge asks to open the terminal and execute the /challenge/run program using relative paths and that relative path should explicitly include '.'. While executing the program, the cwd (current working directory) must be '/'.

### Solve
**Flag:** `pwn.college{8C0loRuMy1HAX8AUWeYo1TmKNvW.QXwUTN0wCM0kDMzEzW}`

To solve this challenge, I first navigated to the root directory '/' to set it as the cwd. From there I executed the program using a relative path with '.' as './challenge/run' because the task specified to explicitly include the current directory in the path which successfully returned the flag.

```bash
cd /
./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{8C0loRuMy1HAX8AUWeYo1TmKNvW.QXwUTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt that in relative paths, '.' can be used to explicitly refer to the cwd. So in this case, './challenge/run' is same as challenge/run. 
