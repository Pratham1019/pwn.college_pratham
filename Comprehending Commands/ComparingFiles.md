# Comprehending Commands

## comparing files
The challenge asks to open the terminal to find the differences between two similar files using the **diff** command to find the flag.

### Solve
**Flag:** `pwn.college{IELuqHZ08PfB3vPiF4NHZEZNgQJ.01MwMDOxwCM0kDMzEzW}`

In this challenge, I used the diff command to find the flag from the decoys_and_real.txt file. I ran the command stated below which successfully returned the flag.

```bash
diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt
27a28
> pwn.college{IELuqHZ08PfB3vPiF4NHZEZNgQJ.01MwMDOxwCM0kDMzEzW}
```

### New Learnings
From this challenge I about the diff command and how it helps to find the differences between two files. For example, in this challenge we were given two files decoys_only.txt and decoys_and_real.txt, first one had 100 fake flags and the second file had the same 100 fake flags + 1 real flag. Thus diff command helped return the "difference" between the two files, aka the real flag.
