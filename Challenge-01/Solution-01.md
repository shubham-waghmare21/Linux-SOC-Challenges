# Linux SOC Challenge 01 - Solution

## Commands Used

```bash
mkdir SOC_Investigation
cd SOC_Investigation

mkdir Logs Evidence Reports Backup
cd Logs

mkdir Authentication Network Malware

touch Authentication/auth.log
touch Network/dns.log Network/firewall.log
touch Malware/malware.log

cp Network/dns.log ../Evidence/dns_evidence.log

cp Authentication/auth.log ../Backup/auth_backup.log

mv Malware/malware.log Malware/ransomware.log

whoami
pwd
free -h
df -h
ps aux

cp Evidence/dns_evidence.log Reports/incident_001.log

tree
ls -al
history
```

---

## What I Learned

- Creating nested directories using `mkdir`
- Creating multiple files with `touch`
- Copying files while renaming them
- Renaming files using `mv`
- Navigating using relative paths
- Viewing system memory and disk usage
- Listing running processes
- Displaying directory structures using `tree`
- Viewing hidden files
- Reviewing command history

---

## Mistakes & Improvements

- Initially used incorrect relative paths while copying files.
- Learned that `cp` can copy and rename a file in a single command.
- Verified the directory structure after each task instead of waiting until the end.
- Improved navigation using relative paths instead of absolute paths.

---

## Result

**Status:** ✅ Completed

**Score:** **92/100**

### Skills Demonstrated

- Linux Navigation
- File & Directory Management
- SOC Investigation Workspace Setup
- Evidence Collection
- System Information Gathering
- Process Enumeration
