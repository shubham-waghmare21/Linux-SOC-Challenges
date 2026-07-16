# Linux SOC Challenge 06 - Solution

## Commands Used

```bash
mkdir SOC_Challenge_06

mkdir Users Reports Evidence Backup

sudo useradd tempanalyst

sudo passwd tempanalyst

su tempanalyst

whoami

exit

grep "tempanalyst" /etc/passwd

grep "tempanalyst" /etc/passwd > Evidence/tempanalyst.txt

cat > Reports/report.txt << EOF
Incident ID : 006
Incident Type : Temporary User Creation
Status : Completed
Analyst : Shubham
EOF

whoami

free -h

df -h

cat > password.txt << EOF
SOC2026!
EOF

od -c password.txt

od -tx1 password.txt

od -b password.txt
```

---

## What I Learned

- Created a temporary Linux user.
- Assigned a password using `passwd`.
- Switched between user accounts using `su`.
- Returned to the original account using `exit`.
- Collected evidence from `/etc/passwd`.
- Redirected command output into evidence files.
- Created reports using Here Documents.
- Displayed file contents in different formats using `od`.

---

## Mistakes & Improvements

- Accidentally typed **tempalalyst** instead of **tempanalyst**, causing the `su` command to fail.
- Learned that `!` is interpreted by the Zsh shell and can cause an `event not found` error.
- Solved the issue by using a Here Document instead of `echo`.

---

## Result

✅ Successfully completed Linux SOC Challenge 06.

**Final Score:** 100/100
