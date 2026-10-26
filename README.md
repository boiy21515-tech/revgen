<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c41d54a4-fa8c-43be-a108-c996b34b6a98" />

# RevGen - Reverse Shell Payload Generator

RevGen is a fast, lightweight, and dependency-free command-line tool written in Python 3. It is designed to quickly generate reverse shell payloads in various programming languages without needing to browse external websites or wait for slow web pages to load.

## Features

- **20 Supported Languages**: Bash, Zsh, Ksh, Python (2 & 3), PHP, PowerShell, Perl, Ruby, Netcat, Socat, Java, Node.js, Golang, Awk, Lua, Telnet, Xterm, C, and C#.
- **Base64 Encoding**: Built-in support for Base64 obfuscation (with proper UTF-16LE handling for PowerShell).
- **URL Encoding**: Quickly URL-encode payloads to bypass basic web filters.
- **Clipboard Integration**: Automatically copy the generated payload to your clipboard using `wl-copy` (Wayland).
- **Zero Dependencies**: Uses only the Python standard library.
- **Pre-built Binary**: Available as a single executable file for Linux (x86_64).

## Installation

### From Source (Python)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/revgen.git
   cd revgen
2. ./revgen -h
