# Comprehending Commands

## more catting practice
The challenge asks to open the terminal and read the flag file located inside a particular directory using the cat command.

### Solve
**Flag:** `pwn.college{UD41zABC_z5vbk8uyEjgyTSpwdB.QX5ETO0wCM0kDMzEzW}`

In this challenge, the flag file was located in the /usr/share/cmake-3.16/ directory.
To solve it, I ran the command 'cat /usr/share/cmake-3.16/flag' which successfully returned the flag.

```bash
You cannot use the 'cd' command in this level, and must retrieve the flag by 
absolute path. Plus, I hid the flag in a different directory! You can find it 
in the file /usr/share/cmake-3.16/flag. Go cat it out **without** cding into 
that directory!

cat /usr/share/cmake-3.16/flag
pwn.college{kfc67PytB6-Utb2XP2XLTHk3-hp.QXwITO0wCM0kDMzEzW}
```

### New Learnings
From this challenge I practiced how to use absolute paths with the cat command.
