# Linux SOC Challenge 01 - SOC Investigation Workspace

## Objective

Practice basic Linux commands by creating and managing a SOC investigation workspace.

---

## Scenario

You have joined CyberShield Security as a SOC Intern.

Your manager has assigned you the task of preparing a Linux workspace for an investigation. Complete all tasks using Linux commands only.

---

## Tasks

### Task 1

Create the following directory structure:

```
SOC_Investigation
├── Logs
│   ├── Authentication
│   ├── Network
│   └── Malware
├── Evidence
├── Reports
└── Backup
```

---

### Task 2

Create the following files:

- auth.log
- dns.log
- firewall.log
- malware.log

---

### Task 3

Copy `dns.log` from the **Network** directory to the **Evidence** directory and rename it to:

```
dns_evidence.log
```

---

### Task 4

Copy `auth.log` to the **Backup** directory as:

```
auth_backup.log
```

---

### Task 5

Rename:

```
malware.log
```

to

```
ransomware.log
```

---

### Task 6

Display the following information:

- Current user
- Current working directory
- RAM usage
- Disk usage
- Running processes

---

### Task 7

Copy `dns_evidence.log` to the **Reports** directory and rename it to:

```
incident_001.log
```

---

### Task 8

Navigate between directories using **relative paths only**.

---

### Task 9

Display:

- Directory tree
- All files (including hidden files)
- Command history

---

## Skills Tested

- Linux Navigation
- Directory Management
- File Management
- Relative Paths
- System Information
- Process Investigation
