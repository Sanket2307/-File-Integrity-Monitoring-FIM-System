📌 Overview

The File Integrity Monitoring (FIM) System is a cybersecurity tool designed to detect unauthorized changes to critical files and directories. It works by creating a secure baseline of file hashes and continuously comparing them to identify modifications, deletions, or new file additions.

This project demonstrates the practical implementation of integrity assurance, a core pillar of information security.

🎯 Objectives

Monitor sensitive files and directories

Detect unauthorized file changes in real time

Maintain file integrity using cryptographic hashing

Log and alert integrity violations

Strengthen system security and auditability

🛠️ Technologies Used

Programming Language: Python

Hashing Algorithm: SHA-256

Operating System: Linux / Windows

Libraries Used:

hashlib

os

time

json

⚙️ How It Works

Selected files and directories are scanned.

A baseline hash is generated using SHA-256.

The baseline is securely stored.

Files are periodically re-scanned.

Any hash mismatch triggers an integrity alert.

🚨 Detection Capabilities

The system detects and logs:

File modifications

File deletions

New file additions

Timestamped integrity violations

🔐 Security Use Cases

Malware detection

Unauthorized access detection

System hardening and auditing

Compliance monitoring (ISO 27001, PCI-DSS)

Server and application security

📈 Future Enhancements

Email / SMS / Telegram alerts

Real-time monitoring using OS-level hooks

Encrypted baseline storage

Web-based dashboard

Cloud-based FIM using AWS services
