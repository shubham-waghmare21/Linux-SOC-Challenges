# Linux SOC Challenge 02 - Solution

## Commands Used

```bash
mkdir SOC_Challenge_02
cd SOC_Challenge_02

mkdir Logs Evidence Report

touch Logs/auth.log Logs/network.log Logs/firewall.log

echo "User kali logged in" >> auth.log
echo "Failed password for root" >> auth.log
...

grep "Failed" auth.log

grep "DNS" network.log

head -2 auth.log

tail -2 auth.log

sort firewall.log

tac network.log

od -b sample.txt

od -tx1 sample.txt

od -c sample.txt

lspci

lsof

sleep 5

echo Investigation Started
```

---

## What I Learned

- Searching log files using grep
- Viewing the beginning and end of log files
- Sorting log entries
- Viewing logs in reverse order
- Inspecting file contents in different formats
- Listing hardware devices
- Viewing open files
- Using sleep to delay execution
- Creating reports using echo

---

## Mistakes & Improvements

- Initially tried `grep` without specifying the file.
- Tried using an invalid option with `sort`.
- Learned that `grep "pattern" filename` is cleaner than using `cat file | grep`.

---

## Result

✅ Successfully completed Linux SOC Challenge 02.

**Score:** 98/100
