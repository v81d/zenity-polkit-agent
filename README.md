# Zenity Polkit Agent

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/v81d/zenity-polkit-agent?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/v81d/zenity-polkit-agent?style=for-the-badge)
![GitHub issues or pull requests](https://img.shields.io/github/issues/v81d/zenity-polkit-agent?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/v81d/zenity-polkit-agent?style=for-the-badge)

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

## Contributing

### Reporting Issues

To report an issue or bug, visit Zenity Polkit Agent's [issue tracker](https://github.com/v81d/zenity-polkit-agent/issues) on GitHub.

### Pull Requests

To push your features or fixes into this official repository:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/my-feature`) or a fix branch (`git checkout -b fix/my-fix`).
3. Commit your changes (`git commit -m "feat: add new feature"`). **Please follow the [Conventional Commits](https://www.conventionalcommits.org) guideline when doing so!**
4. Push the branch (`git push origin feature/my-feature`).
5. Open a pull request with `contrib` as the base branch. Make sure to create a detailed title and description of your change.

Please follow the [GitHub flow](https://guides.github.com/introduction/flow) and Zenity Polkit Agent's [Code of Conduct](CODE_OF_CONDUCT.md) when submitting a pull request.

## License

Zenity Polkit Agent is free software distributed under the **GNU General Public License, version 3.0 or later (GPL-3.0+).**

You are free to use, modify, and share the software under the terms of the GPL.
For full details, see the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).
