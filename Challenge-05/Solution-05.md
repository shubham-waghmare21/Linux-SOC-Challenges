# Linux SOC Challenge 05 - Solution

## Commands Used

```bash
mkdir SOC_Challenge_05

mkdir Users Evidence Reports Backup

sudo useradd analyst
sudo useradd developer
sudo useradd guest

cat /etc/passwd

cat /etc/passwd > Evidence/users.txt

cat > Reports/report.txt << EOF
Incident ID : 005
Incident Type : User Investigation
Status : Completed
Analyst : Shubham
EOF

whoami

free -h

df -h

echo BlueTeam2026 > admin.txt

od -c admin.txt

od -tx1 admin.txt

od -b admin.txt

grep "analyst" /etc/passwd

grep "developer" /etc/passwd
```

---

## What I Learned

- Created new Linux users.
- Viewed the Linux user database.
- Redirected command output into evidence files.
- Used grep to search for specific users.
- Created reports using Here Documents.
- Practiced basic Linux system administration commands.

---

## Mistakes & Improvements

- Initially forgot the leading `/` in `/etc/passwd`.
- Forgot to create `Evidence/users.txt`, then corrected it by redirecting the output of `cat /etc/passwd`.
- Improved understanding of Linux output redirection.

---

## Result

✅ Successfully completed Linux SOC Challenge 05.

**Final Score:** 100/100
