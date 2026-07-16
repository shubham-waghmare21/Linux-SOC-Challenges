# Linux SOC Challenge 06 - Temporary Analyst Account

## Objective

Practice Linux user management by creating a temporary analyst account, assigning a password, switching users, collecting evidence, and documenting the activity.

---

## Scenario

A temporary SOC analyst has joined today's shift.

Your Team Lead asks you to create a temporary account, verify it works correctly, and prepare documentation for the account creation.

---

## Tasks

### Task 1

Create the following directory structure:

```text
SOC_Challenge_06
├── Users
├── Reports
├── Evidence
└── Backup
```

---

### Task 2

Create the following user:

- tempanalyst

---

### Task 3

Assign a password to the newly created user.

---

### Task 4

Switch to the **tempanalyst** account.

Verify that the account is working correctly.

---

### Task 5

Return to the original account.

---

### Task 6

Display only the information related to:

```text
tempanalyst
```

from:

```text
/etc/passwd
```

---

### Task 7

Create:

```text
Evidence/tempanalyst.txt
```

Store only the information related to **tempanalyst**.

---

### Task 8

Create:

```text
Reports/report.txt
```

using a Here Document.

Content:

- Incident ID : 006
- Incident Type : Temporary User Creation
- Status : Completed
- Analyst : Shubham

---

### Task 9

Display:

- Current user
- Memory usage
- Disk usage

---

### Task 10

Create:

```text
password.txt
```

Store:

```text
SOC2026!
```

Display the file in:

- Character format
- Hexadecimal format
- Binary format

---

## Bonus

1. Switch to **tempanalyst**.
2. Verify using `whoami`.
3. Return to the original account.
4. Explain whether the user can use `sudo` by default.

---

## Skills Practiced

- useradd
- passwd
- su
- exit
- grep
- cat
- Here Documents
- Output Redirection
- whoami
- free
- df
- od
