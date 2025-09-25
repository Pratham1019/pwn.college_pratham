# Comprehending Commands

## catting absolute paths
The challenge asks to open the terminal and read the flag file using its absolute path with the cat command.

### Solve
**Flag:** `pwn.college{UD41zABC_z5vbk8uyEjgyTSpwdB.QX5ETO0wCM0kDMzEzW}`

In this challenge, the flag file was located at the root directory.
To solve it, I ran the command 'cat /flag' which successfully returned the flag.

```bash
cat /flag
pwn.college{UD41zABC_z5vbk8uyEjgyTSpwdB.QX5ETO0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt about how to use absolute paths with the cat command.
