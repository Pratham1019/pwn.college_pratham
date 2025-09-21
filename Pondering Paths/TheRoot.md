# Pondering Paths

## The Root
The challenge asks you to open the terminal in the pwn.college DOJO and run the pwn program from the root directory using its absolute path /pwn to get the flag.

### Solve
**Flag:** `pwn.college{E_MZUCd99TDcCukSeieSJajOi6d.QX4cTO0wCM0kDMzEzW}`

In this challenge, the pwn program was stored in the root directory and we had to access it to capture the flag.

For solving this challege, I executed the pwn program using its absolute path '/pwn' which sucessfully returned the flag.

```bash
/pwn
BOOM!!!
Here is your flag:
pwn.college{E_MZUCd99TDcCukSeieSJajOi6d.QX4cTO0wCM0kDMzEzW}
```

### New Learnings
From this challenge, I learnt how to use an absolute path (/...) and the difference between accessing files using absolute paths v/s relative paths.
### References 
pwn.college | 
Linux Luminarium - 2 The File System - https://www.youtube.com/watch?v=b67Jq6IZ3U8&list=PL-ymxv0nOtqqRAz1x90vxNbhmSkeYxHVC
