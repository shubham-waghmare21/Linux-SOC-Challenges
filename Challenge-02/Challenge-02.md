# Linux SOC Challenge 02 - Log Investigation Basics

## Objective

Practice Linux log analysis using basic text-processing and system commands commonly used by SOC analysts.

---

## Scenario

You have started your morning shift as a SOC Analyst.

The SOC team has received several log files that must be reviewed before the senior analyst arrives. Your task is to organize the logs, inspect their contents, and perform basic investigations using Linux commands.

---

## Tasks

### Task 1
Create the following directory structure:
'''text
SOC_Challenge_02
├── Logs
├── Evidence
└── Report
'''

### Task 2
Create the following log files:

- auth.log
- network.log
- firewall.log

### Task 3
Populate each log file with the provided data using Linux commands only.

### Task 4
Search for all failed login attempts.

### Task 5
Search for all DNS-related activity.

### Task 6
Display the first two and last two lines of the authentication log.

### Task 7
Sort the firewall log alphabetically.

### Task 8
Display the network log in reverse order.

### Task 9
Create a sample file and inspect it using:

- Character format
- Hexadecimal format
- Binary format

### Task 10
Display PCI hardware devices.

### Task 11
Display currently opened files.

### Task 12
Pause execution for five seconds and display:

Investigation Started

### Bonus

Create a report containing:

Incident ID : 002

Status : Open

Analyst : Shubham

without using nano or vi.

---

## Skills Practiced

- grep
- head
- tail
- sort
- tac
- od
- lspci
- lsof
- sleep
- echo
