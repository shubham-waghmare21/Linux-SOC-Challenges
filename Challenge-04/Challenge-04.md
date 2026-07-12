# Linux SOC Challenge 04 - Suspicious User Investigation

## Objective

Practice investigating authentication logs, collecting evidence, and preparing an incident report using Linux commands commonly used by SOC analysts.

---

## Scenario

A system administrator reports that several users were unable to log in this morning. The SOC team suspects an unauthorized access attempt.

As the SOC Analyst, your responsibility is to investigate the authentication logs, collect evidence, and prepare a basic incident report.

---

## Tasks

### Task 1

Create the following directory structure:

```text
SOC_Challenge_04
├── Logs
├── Evidence
├── Reports
├── Backup
└── Archive
```

---

### Task 2

Create the following log files inside the **Logs** directory:

- auth.log
- ssh.log
- system.log

---

### Task 3

Populate each log file using Linux commands only (without using nano or vi).

---

### Task 4

Create the following evidence files inside the **Evidence** directory:

- failed_auth.log
- successful_auth.log
- ssh_failed.log

Store only the relevant log entries inside each evidence file.

---

### Task 5

Display:

- First 2 lines of auth.log
- Last 2 lines of auth.log

---

### Task 6

Display the authentication log from newest to oldest.

---

### Task 7

Display all three log files in alphabetical order.

---

### Task 8

Create:

admin_password.txt

Store:

SOC@2026

Display the file using:

- Character format
- Hexadecimal format
- Binary format

---

### Task 9

Display:

- Current user
- Memory usage
- Disk usage
- PCI devices
- Open files

---

### Task 10

Pause execution for five seconds.

Display:

Investigation Finished Successfully

---

## Bonus Tasks

- Count failed login attempts.
- Count successful logins.
- Create an incident report.
- Display only log entries containing "root".

---

## Skills Practiced

- Here Documents (cat << EOF)
- grep
- head
- tail
- tac
- sort
- od
- whoami
- free
- df
- lspci
- lsof
- sleep
- Linux investigation workflow
