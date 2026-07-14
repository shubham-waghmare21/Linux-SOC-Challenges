# Linux SOC Challenge 05 - Unauthorized User Investigation

## Objective

Practice basic Linux user management by creating users, inspecting the system user database, collecting evidence, and preparing an investigation report.

---

## Scenario

The SOC team receives an alert that unauthorized user accounts may have been created on a Linux server.

As the SOC Analyst, your task is to verify user accounts, collect evidence, and prepare a basic investigation report.

---

## Tasks

### Task 1

Create the following directory structure:

```text
SOC_Challenge_05
├── Users
├── Evidence
├── Reports
└── Backup
```

---

### Task 2

Create the following users:

- analyst
- developer
- guest

---

### Task 3

Display all system users using the Linux user database.

---

### Task 4

Create:

```text
Evidence/users.txt
```

Store the contents of the Linux user database inside the file.

---

### Task 5

Create:

```text
Reports/report.txt
```

using a Here Document.

Include:

- Incident ID : 005
- Incident Type : User Investigation
- Status : Completed
- Analyst : Shubham

---

### Task 6

Display:

- Current user
- Memory usage
- Disk usage

---

### Task 7

Create:

```text
admin.txt
```

Store:

```text
BlueTeam2026
```

Display the file using:

- Character format
- Hexadecimal format
- Binary format

---

## Bonus Tasks

- Display only the user information for **analyst**.
- Display only the user information for **developer**.

---

## Skills Practiced

- useradd
- cat
- grep
- Output Redirection (>)
- Here Documents (<< EOF)
- whoami
- free
- df
- od
