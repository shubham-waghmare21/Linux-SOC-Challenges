# Linux SOC Challenge 03 - Solution

## Commands Used

```bash
mkdir SOC_Challenge_03

mkdir Logs Evidence Reports Backup

touch Logs/auth.log

echo "...">>auth.log

grep "Failed" auth.log

head -3 auth.log

tail -3 auth.log

tac auth.log

sort auth.log

od -c password.txt

od -tx1 password.txt

od -b password.txt

lsof

lspci

sleep 3

echo Investigation Complete
```

---

## What I Learned

- Created and managed investigation directories.
- Used grep to filter failed login attempts.
- Viewed the beginning and end of log files using head and tail.
- Reversed log timelines using tac.
- Sorted log entries alphabetically.
- Inspected file contents in character, hexadecimal, and binary formats.
- Used sleep to simulate investigation timing.
- Learned to troubleshoot command syntax errors independently.

---

## Mistakes & Improvements

- Initially attempted to write multiple log entries using a single `echo` command incorrectly.
- Forgot to populate the evidence files after creating them.
- Used an incorrect option (`od -txt1`) before correcting it to `od -tx1`.
- Successfully diagnosed and corrected command errors without assistance.

---

## Result

✅ Successfully completed Linux SOC Challenge 03.

**Score:** 95/100
