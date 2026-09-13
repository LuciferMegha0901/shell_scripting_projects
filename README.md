# Shell Scripting Projects 🐚

A collection of practical shell scripting projects designed to automate common tasks, demonstrate best practices, and serve as learning resources for shell scripting enthusiasts.

## 📋 Table of Contents

- [About](#about)
- [Projects](#projects)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

This repository contains a variety of shell scripting projects written primarily in **Bash**, covering everything from beginner-friendly utilities to advanced automation scripts. Each project is self-contained with its own documentation and examples.

Whether you're:
- 📚 Learning shell scripting
- 🔧 Looking for automation solutions
- 🚀 Building your DevOps toolkit
- 🎓 Teaching others

...you'll find something useful here.

## Projects

| Project | Description | Difficulty |
|---------|-------------|------------|
| system-monitor/ | Real-time CPU, memory, and disk usage monitor | Beginner |
| backup-automation/ | Automated backup script with rotation and compression | Intermediate |
| log-analyzer/ | Parse and analyze log files with reporting | Intermediate |
| git-helpers/ | Handy Git workflow automation scripts | Beginner |
| batch-renamer/ | Bulk file renaming with regex support | Beginner |
| server-health-check/ | Check server health and send alerts | Advanced |
| docker-cleanup/ | Clean up unused Docker resources | Intermediate |
| password-generator/ | Secure password generator | Beginner |
| file-organizer/ | Organize files into folders by type/date | Intermediate |
| network-scanner/ | Simple network scanning utility | Advanced |

> **Note:** Update this table as you add new projects.

## Prerequisites

- **Bash** 4.0+ (or Zsh)
- **Coreutils** (standard on Linux/macOS)
- Optional tools depending on the project:
  - curl, jq, awk, sed, grep
  - docker (for Docker-related scripts)
  - git

### Installation

**Linux (Debian/Ubuntu):**
    sudo apt update && sudo apt install -y bash coreutils curl jq

**macOS:**
    brew install bash coreutils jq

## Getting Started

Clone the repository:

    git clone https://github.com/yourusername/shell-scripting-projects.git
    cd shell-scripting-projects

Make scripts executable:

    chmod +x **/*.sh

## Usage

Each project lives in its own directory with a dedicated README.md. Navigate to a project and follow its instructions:

    cd system-monitor
    ./monitor.sh --help

### Example: System Monitor

    ./system-monitor/monitor.sh --interval 5 --log /var/log/sysmon.log

### Example: Backup Automation

    ./backup-automation/backup.sh -s /home/user/docs -d /mnt/backups -r 7

## Project Structure

    shell-scripting-projects/
    ├── README.md
    ├── LICENSE
    ├── .gitignore
    ├── system-monitor/
    │   ├── README.md
    │   ├── monitor.sh
    │   └── config.example
    ├── backup-automation/
    │   ├── README.md
    │   ├── backup.sh
    │   └── restore.sh
    ├── log-analyzer/
    │   ├── README.md
    │   └── analyze.sh
    └── ...

Each project typically includes:
- README.md — Project-specific documentation
- *.sh — Main script(s)
- config.example — Sample configuration
- tests/ — Optional test scripts

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch:

       git checkout -b feature/amazing-script

3. **Commit** your changes:

       git commit -m "Add amazing new script"

4. **Push** to the branch:

       git push origin feature/amazing-script

5. **Open** a Pull Request

### Contribution Guidelines

- Use #!/usr/bin/env bash as the shebang
- Run scripts through shellcheck (https://www.shellcheck.net/) before submitting
- Include a README.md for each new project
- Add usage examples and comments where helpful
- Follow existing naming conventions

## License

This project is licensed under the **MIT License** — see the LICENSE file for details.

## Contact

- **Author:** Your Name
- **GitHub:** @yourusername
- **Email:** your.email@example.com

---

⭐ If you find this repository useful, please consider giving it a star!
EOF
