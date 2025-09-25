# Comprehending Commands

## grepping for a needle in a haystack
The challenge asks to open the terminal to search the flag from 1,00,000 line text file located at /challenge/data.txt using the **grep** command.

### Solve
**Flag:** `pwn.college{wVypXJ0IEFtLWod-09oINUIQM3c.QX3EDO0wCM0kDMzEzW}`

In this challenge, the flag was located the /challenge/data.txt file (a text file of 100k lines)

To solve it, I used the grep command which search for lines containing specific strings in the file. I searched for "pwn.college" string inside the file which is present in every flag. This successfilly returned the flag.

```bash
grep pwn.college /challenge/data.txt
pwn.college{wVypXJ0IEFtLWod-09oINUIQM3c.QX3EDO0wCM0kDMzEzW}
```

### New Learnings
From this challenge I about the grep command and how it helps returning all lines that contain a match for the specified string.
