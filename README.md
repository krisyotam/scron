# Kris's build of scron

My build of [scron](https://git.2f30.org/scron/), a simple cron daemon.

---

## About

scron is a minimal cron daemon designed to be simple and secure. It replaces the traditional cron daemon with a cleaner, more auditable implementation.

---

## Features

- **Simple**: Minimal codebase, easy to understand and audit
- **Secure**: Runs with minimal privileges
- **Compatible**: Standard crontab format support
- **Lightweight**: No dependencies beyond libc

---

## Usage

```bash
# Start the daemon
scron

# Crontab location
~/.config/scron/crontab
# or
/etc/crontab
```

### Crontab Format

```
# min hour day month weekday command
0    *    *   *     *       /path/to/script
*/5  *    *   *     *       every-five-minutes.sh
0    0    *   *     *       daily-midnight.sh
```

---

## Installation

```bash
git clone https://github.com/krisyotam/scron
cd scron
sudo make install
```

---

## Other Suckless Repos

- [dwm](https://github.com/krisyotam/dwm) - dynamic window manager
- [st](https://github.com/krisyotam/st) - simple terminal
- [dmenu](https://github.com/krisyotam/dmenu) - dynamic menu
- [dwmblocks](https://github.com/krisyotam/dwmblocks) - modular status bar
- [quark](https://github.com/krisyotam/quark) - tiny HTTP server

---

## Contact

- Kris Yotam <krisyotam@protonmail.com>
- [https://krisyotam.com](https://krisyotam.com)
