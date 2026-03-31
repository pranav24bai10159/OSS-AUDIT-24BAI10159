# OSS Audit Project — Linux Kernel

## Student Details

* Name: Pranav K Santhosh
* Course: Open Source Software
* Project Title: Open Source Audit — Linux Kernel

---

## Chosen Software: Linux Kernel

The Linux Kernel is the core component of the Linux operating system. It manages hardware resources, system processes, memory, and device communication. It is released under the GNU General Public License v2 (GPL v2) and is one of the most important open-source projects in the world.

---

## Project Description

This project is an audit and analysis of the Linux Kernel as part of the Open Source Software course. It includes:

* Study of the origin and philosophy of Linux
* Analysis of its open-source license (GPL v2)
* Understanding its role in the Linux ecosystem
* Comparison with proprietary systems
* Implementation of 5 Linux shell scripts demonstrating practical skills

---

## Requirements

* Linux OS (Ubuntu / Kali / Fedora recommended)
* Bash shell
* Basic Linux commands installed (coreutils, grep, awk, etc.)

---

## Project Structure

oss-audit/
│── script1.sh
│── script2.sh
│── script3.sh
│── script4.sh
│── script5.sh
│── README.md

---

## Shell Scripts Overview

### Script 1 — System Identity Report

Displays:

* Kernel version
* Logged-in user
* System uptime
* Linux distribution
* Current date and time
* License information

Concepts used:

* Variables
* Command substitution
* echo

---

### Script 2 — FOSS Package Inspector

Checks if a package (Linux Kernel) is installed and displays:

* Version
* Description
* License

Includes a case statement to describe the software.

Concepts used:

* if-else
* case statement
* grep

---

### Script 3 — Disk and Permission Auditor

Analyzes system directories:

* /etc
* /var/log
* /home
* /usr/bin
* /tmp

Displays:

* Permissions
* Owner
* Disk usage

Concepts used:

* for loop
* awk
* du, ls

---

### Script 4 — Log File Analyzer

Reads a log file and:

* Counts occurrences of a keyword (default: "error")
* Displays last 5 matching lines

Concepts used:

* while loop
* if condition
* command-line arguments

---

### Script 5 — Open Source Manifesto Generator

Interactive script that:

* Takes user input
* Generates a personalized open-source statement
* Saves output to a file

Concepts used:

* read
* string handling
* file output

---

## How to Run the Scripts

### Step 1: Give execution permission

```bash
chmod +x *.sh
```

### Step 2: Run scripts

Script 1

```bash
./script1.sh
```

Script 2

```bash
./script2.sh
```

Script 3

```bash
./script3.sh
```

Script 4

```bash
./script4.sh /var/log/syslog error
```

Script 5

```bash
./script5.sh
```

---

## Learning Outcomes

* Understanding of open-source philosophy
* Hands-on experience with Linux commands
* Shell scripting fundamentals
* System-level analysis in Linux
* Awareness of software licensing

---

## Importance of Linux Kernel

The Linux Kernel powers:

* Android smartphones
* Servers and cloud infrastructure
* Supercomputers
* Embedded systems

It is a strong example of collaborative open-source development.

---

## License

This project is for academic purposes.
Linux Kernel is licensed under GPL v2.

---

## Conclusion

This project helped in understanding both the technical and philosophical aspects of open source. The Linux Kernel demonstrates how collaborative development can power the modern digital world.

---

