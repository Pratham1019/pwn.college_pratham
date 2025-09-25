# Comprehending Commands

## cat: not the pet, but the command!
The challenge asks to open the terminal and read the flag file in your home directory using cat command.

### Solve
**Flag:** `pwn.college{QlKtHqEnF0qhN7zRrdxVbck3feq.QXxcTN0wCM0kDMzEzW}`

To solve this challenge, I ran the command 'cat flag' which successfully returned the flag.

```bash
cat flag
pwn.college{QlKtHqEnF0qhN7zRrdxVbck3feq.QXxcTN0wCM0kDMzEzW}
```

### New Learnings
From this challenge I learnt about the cat (concatenate) command and how its used to read out the files onto the terminal. The cat command works as follows 

```bash
cat <path of the file to be read>
```
