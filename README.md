# Web Server - System Engineering & DevOps

## Description
This project focuses on understanding web server architecture, HTTP protocols, DNS records, and automating server setup using Bash scripts on Ubuntu 16.04 LTS.

## Learning Objectives
At the end of this project, you are expected to be able to explain:
- The main role of a web server and why parent/child process architectures are used.
- Common HTTP request methods (`GET`, `POST`) and response status codes (`200`, `301`, `404`).
- DNS record types (`A`, `CNAME`, `TXT`, `MX`) and how domain names map to IP addresses.
- Task automation using Bash scripts compliant with `ShellCheck`.

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- Operating System: Ubuntu 16.04 LTS
- All files must end with a new line.
- All Bash scripts must be executable and start with `#!/usr/bin/env bash`.
- All Bash scripts must pass `ShellCheck` (version 0.3.7) without error.
- You cannot use `systemctl` to restart Nginx.

## File Descriptions

| Directory | File | Description |
| --- | --- | --- |
| `web_server/` | `0-transfer_file` | Bash script that transfers a file to a remote server using `scp`. |
| `web_server/` | `1-install_nginx_web_server` | Bash script that installs and configures Nginx to listen on port 80 and serve "Holberton School". |
| `web_server/` | `2-setup_a_domain_name` | Text file containing the custom `.tech` domain name configured with an `A` record. |
| `web_server/` | `3-redirection` | Bash script that configures Nginx with a 301 Moved Permanently redirection for `/redirect_me`. |
| `web_server/` | `4-not_found_page_404` | Bash script that configures Nginx with a custom 404 page containing "Ceci n'est pas une page". |
| `web_server/` | `5-design_a_beautiful_404_page.html` | Custom HTML document designed for 404 response pages. |

