# Package Management
---

| Feature     | apt                       | pacman               | dnf                   |
| ---         | ---                       | ---                  | ---                   |  
| Install     | apt install `name(s)`     | pacman -S `name(s)`  | dnf install `name(s)` |
| Uninstall   | apt remove `name(s)`      | pacman -R `name(s)`  | dnf erase `name(s)`   |
| Update      | apt update && apt upgrade | pacman -Syu          | dnf update            |
| Search      | apt search `name(s)`      | pacman -Ss `name(s)` | dnf search `name(s)`  |
| Info        | apt info `name(s)`        | pacman -Qi `name(s)` | dnf info `name(s)`    |
| File format | .deb                      | .pkg.tar.zst         | .rpm                  |

---
### [Return to Index](../)