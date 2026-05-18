## ygmsec

### First Project
* **[Fstab Protection Tool](https://github.com/YGMsec/guardian-fstab-project)** - A utility written in C designed to safeguard the `fstab` file configuration against potential system boot failures (caused by human error, unexpected update behaviors...)

### Current Project
* **Log Analyzer in C** - A low-level log parser designed to monitor and flag anomalies in system behavior.
* *Also building experimental tools to learn how fork() manages Unix processes, with the goal of writing my own background daemons out of technical curiosity.*

### Upcoming Project
* **flcarve (Forensic Log Recovery)** - A low-level DFIR (Digital Forensics and Incident Response) utility designed to recover deleted data during post-exploitation analysis or incident investigations. This tool was conceived to solve a critical real-world scenario: when a genuine attack is mistaken for a false positive, allowing automated `logrotate` policies to unlink and discard critical compressed logs (`.gz`). Since standard system tools fail once unlinked, this utility bypasses the `ext4` inode table metadata to perform raw file carving directly on a disk image (`dd`). By scanning raw storage blocks for gzip magic signatures (`0x1F 0x8B`), it reconstructs and extracts deleted evidence, demonstrating how data persists on disk after deletion. *(Planned purely as an educational exercise to guide my low-level learning journey).*

### Currently Learning
* Linux Internals & Kernel Concepts
* C Programming
* Ethical Hacking & Cybersecurity Foundations

### Programming Languages & Scripting
* **C** (Core language)
* **Bash** (Basic scripting for automation)
* **Python** (Basic foundations)

### Reading List 

#### Currently Reading
* 📖 *The C Programming Language* — Brian W. Kernighan & Dennis M. Ritchie
* 📖 *How Linux Works* — Brian Ward

#### Essential Backlog
* 🎯 *Computer Systems: A Programmer's Perspective* (CS:APP) — Randal E. Bryant & David R. O'Hallaron
* 🎯 *The Linux Programming Interface* — Michael Kerrisk
* 🎯 *The Web Application Hacker's Handbook* — Dafydd Stuttard & Marcus Pinto
* 🎯 *TCP/IP Illustrated, Volume 1: The Protocols* — Kevin R. Fall & W. Richard Stevens


### Pioneers & Researchers I Like
* **Dennis Ritchie**
* **PortSwigger Security Research Team**
* **Rana Khalil**

