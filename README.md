# Zenity Polkit Agent

Zenity Polkit Agent is a polkit authentication agent built with [Zenity](https://gitlab.gnome.org/GNOME/zenity) and [cmd-polkit](https://github.com/OmarCastro/cmd-polkit).

## Quick Start

The following guide provides instructions on how to build and run Zenity Polkit Agent.

### Prerequisites

Make sure you have the following packages installed:

- [Bash](https://www.gnu.org/software/bash)
- [jq](https://jqlang.org)
- [Zenity](https://gitlab.gnome.org/GNOME/zenity)
- [cmd-polkit](https://github.com/OmarCastro/cmd-polkit)

### Installation

To install Zenity Polkit Agent, follow the instructions below.

1. Clone the repository:

```bash
git clone https://github.com/v81d/zenity-polkit-agent.git
cd zenity-polkit-agent
```

2. Make the program an executable:

```bash
chmod +x zenity-polkit-agent
```

3. Run the program:

```bash
./zenity-polkit-agent
```

You can also turn this into a systemd service or simply create an autostart script.

## License

Zenity Polkit Agent is free software distributed under the **GNU General Public License, version 3.0 or later (GPL-3.0+).**

You are free to use, modify, and share the software under the terms of the GPL.
For full details, see the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).
