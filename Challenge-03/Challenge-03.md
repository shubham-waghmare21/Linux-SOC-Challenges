# Linux SOC Challenge 03 - Failed Login Investigation

## Objective

Practice Linux log analysis by identifying failed and successful login attempts using common Linux commands.

---

## Scenario

You are working as a SOC Analyst.

The SOC team has received an alert indicating multiple failed login attempts on a Linux server. Your task is to investigate the authentication logs and prepare evidence for the senior analyst.

---

## Tasks

### Task 1
Create the following directory structure:

Incident_003
├── Logs
├── Evidence
├── Reports
└── Backup

### Task 2
Create the authentication log file:

- auth.log

### Task 3
Populate the log file with the provided authentication events using Linux commands only.

### Task 4
Create the following evidence files:

- failed_attempts.log
- successful_logins.log

Store only the relevant log entries in each file.

### Task 5
Display:

- First 3 log entries
- Last 3 log entries

### Task 6
Display the authentication log in reverse order.

### Task 7
Display all log entries in alphabetical order.

### Task 8
Create a file named:

password.txt

Store:

SOC123

Display the file contents using:

- Character format
- Hexadecimal format
- Binary format

### Task 9
Display:

- Open files
- PCI hardware devices

### Task 10
Pause execution for 3 seconds and display:

Investigation Complete

### Bonus

Determine how many failed login attempts occurred.

---

## Skills Practiced

- grep
- head
- tail
- tac
- sort
- od
- lsof
- lspci
- sleep
- echo
