# Linux SOC Challenge 04 - Solution

## Commands Used

```bash
mkdir SOC_Challenge_04

mkdir Logs Evidence Reports Backup Archive

touch Logs/auth.log Logs/ssh.log Logs/system.log

cat > auth.log << EOF
...
EOF

cat > ssh.log << EOF
...
EOF

cat > system.log << EOF
...
EOF

grep "Failed" ../Logs/auth.log > failed_auth.log

grep "User" ../Logs/auth.log > successful_auth.log

grep "failed" ../Logs/ssh.log > ssh_failed.log

head -2 auth.log

tail -2 auth.log

tac auth.log

sort auth.log ssh.log system.log

od -c admin_password.txt

od -tx1 admin_password.txt

od -b admin_password.txt

whoami

free -h

df -h

lspci

lsof

sleep 5

echo "Investigation Finished Successfully"
```

---

## What I Learned

- Creating multi-line files using Here Documents.
- Using grep with output redirection to build evidence files.
- Viewing log summaries using head and tail.
- Reversing timelines using tac.
- Sorting logs alphabetically.
- Inspecting files in different formats using od.
- Collecting basic system information.
- Preparing SOC investigation reports.

---

## Mistakes & Improvements

- Initially forgot to redirect grep output into evidence files.
- Accidentally created the incident report in the wrong location before correcting the approach.
- Learned that Here Documents are much more efficient than multiple echo commands.
- Improved troubleshooting by identifying and correcting mistakes independently.

---

## Result

✅ Successfully completed Linux SOC Challenge 04.

**Score:** 96/100
