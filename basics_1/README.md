# Holberton School - Networking (Basics 1)

This repository contains tasks and scripts covering fundamental networking concepts, including IP addressing (`localhost`, `127.0.0.1`, `0.0.0.0`), host configuration (`/etc/hosts`), and active network interfaces.

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- Interpreted on **Ubuntu 22.04**
- All files should end with a new line
- All Bash scripts must be executable and pass **Shellcheck (version 0.7.0)** without errors
- The first line of all Bash scripts must be exactly `#!/usr/bin/env bash`

---

## Tasks

### 0. Change your home IP
* **File:** `0-change_your_home_IP`
* **Description:** A Bash script that modifies the local `/etc/hosts` file to change name resolution:
  * `localhost` resolves to `127.0.0.2`
  * `facebook.com` resolves to `8.8.8.8`
* **Usage:**
  ```bash
  chmod +x 0-change_your_home_IP
  sudo ./0-change_your_home_IP
