#Learning – Bash Scripting 

This repository documents my hands-on journey through the learning of Bash, where I built a deep and practical foundation in Bash scripting — the backbone of modern DevOps and automation workflows.


---

## 📁 Repository Structure
DevOps-Bash/
├── lessons/               # One script per lesson (35 total)
├── battle_arena/          # Bash Battle Arena levels 1–15
├── extras/                # Optional bonus or creative scripts
└── README.md              # You’re reading it!

---

## 🎮 Bash Battle Arena – Game Mode Scripting

The Bash Battle Arena is a simulation-based CLI game created by CoderCo to train DevOps thinking. I completed **all 15 levels**, each introducing a new challenge in scripting automation:

| Level | Script                        | Concept                     |
|-------|-------------------------------|-----------------------------|
| 1     | `level01_arena_setup.sh`      | File creation               |
| 2     | `level02_loop_numbers.sh`     | Loops                       |
| 3     | `level03_hero_check.sh`       | File presence conditions    |
| 4     | `level04_file_ops.sh`         | Copy files, check existence |
| 5     | `level05_boss1.sh`            | Combined logic & file ops   |
| 6     | `level06_argument_lines.sh`   | Count file lines by arg     |
| 7     | `level07_sort_txt.sh`         | Sort files by size          |
| 8     | `level08_log_searcher.sh`     | Search across `.log` files  |
| 9     | `level09_directory_monitor.sh`| Directory change monitoring |
| 10    | `level10_boss2.sh`            | Multi-step file handling    |
| 11    | `level11_disk_alert.sh`       | Disk usage checker          |
| 12    | `level12_config_parser.sh`    | Parse config files          |
| 13    | `level13_backup_rotator.sh`   | Keep latest 5 backups only  |
| 14    | `level14_menu_script.sh`      | Build interactive menus     |
| 15    | `level15_boss3_menu.sh`       | Full menu + backups + status|

➡️ All scripts are in the `battle_arena/` folder.

---

## 🛠️ Extra Scripts (from Creative & Challenge Tasks)

| Script Name               | Description                                  |
|---------------------------|----------------------------------------------|
| `log_searcher.sh`         | Search across all `.log` files recursively   |
| `monitor_directory.sh`    | Logs file changes with timestamps            |
| `backup_rotator.sh`       | Keeps only the 5 latest backups              |
| `config_parser.sh`        | Reads `KEY=VALUE` pairs from config files    |
| `disk_usage_alert.sh`     | Alerts if disk usage exceeds threshold       |

➡️ Located in the `extras/` folder.

---

## 🧠 Key Takeaways

- 📁 I learned how to **structure reusable scripts** for real-world DevOps tasks  
- 🔁 Loops, flags, and conditionals became second nature  
- ⚠️ I practiced **error-proof scripting** using `set -eux` and exit codes  
- 📜 I learned to **read logs, process files**, and script backups, alerts, and monitors  
- 🧰 Bash became a **toolbox**, not just a language

---

## 🗃️ GitHub Portfolio Value

✅ 50+ real Bash scripts  
✅ Covers all DevOps scripting building blocks  
✅ Demonstrates structure, readability, and CLI thinking  
✅ Ready to plug into Ansible, CI/CD, cron jobs, or IaC logic


