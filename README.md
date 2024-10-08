# Malware Analysis Tools

This repository contains tools, scripts, and guides for performing malware analysis, both statically and dynamically.

## Directories:

- `setup-scripts/`: Contains installation scripts for popular malware analysis tools like Volatility and Rekall.
- `static-analysis/`: Scripts and guides for disassembling malware, using tools like Ghidra and IDA Pro.
- `dynamic-analysis/`: Tools and scripts for setting up automated environments for dynamic malware analysis.
- `memory-forensics/`: Scripts for acquiring and analyzing memory dumps from infected systems.
- `scripts/`: General-purpose Python scripts for malware deobfuscation and decompilation.
- `tools/`: Custom YARA scanning and packet inspection tools.

## Quick Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/14mb1v45h/cyberspace017.git

2. Install Volatility:
   ```bash
   cd cyberspace017/setup-scripts
   bash install-volatility.sh

3. Clone the repository:
   ```bash
   bash install-rekall.sh
   
3. Run a YARA scan::
   ```bash
   python3 tools/yarascan.py
