<div align="center">

# kaiHEN

### Homebrew Environment for Nintendo Switch 2

An experimental homebrew enabler and minimal custom firmware project for Nintendo Switch 2.

[Official GitHub Repository](https://github.com/ouncebrew/kaihen) · [Developer Toolkit](https://github.com/ouncebrew/ounce-devkit)

</div>

## Product Overview

kaiHEN is an experimental homebrew environment and minimal custom firmware for Nintendo Switch 2, developed by the ouncebrew project.

It provides a system-level environment for loading homebrew applications, running plugins, and developing native software for Switch 2. Its architecture includes a startup program, a HEN service, an NRO loading service, and a dedicated homebrew API.

The project also introduces development infrastructure intended to help port compatible Nintendo Switch homebrew applications to Switch 2.

The publicly identified build is **20261114d**, published in November 2026. The project remains under active development.

## Technical Architecture

kaiHEN is organized into several cooperating components:

- **RO (`ro/`):** Implements the `ldr:ro` service, maps NRO applications into client processes, and provides JIT code functionality.
- **Bootstrap (`bootstrap/`):** Startup program that initializes HEN and plugins and establishes their required service sessions.
- **HEN (`hen/`):** Main homebrew environment service. Starts the homebrew loader and provides the homebrew interface.
- **libkaihen (`libkaihen/`):** Homebrew API with additional JIT support.
- **Common (`common/`):** Shared protocol definitions and common code used by the other components.

## Key Features

- Homebrew environment for Nintendo Switch 2.
- Minimal custom firmware architecture.
- NRO application loading.
- Homebrew loader integration.
- JIT code support.
- Dedicated homebrew API.
- Plugin startup and session management.
- System-service integration.
- Development toolkit compatibility.
- Support for porting compatible Switch 1 homebrew.
- Open-source implementation under documented licensing terms.

## Module Overview

| Module | Function |
|---|---|
| `ro/` | NRO mapping and JIT functionality |
| `bootstrap/` | Startup and component initialization |
| `hen/` | Homebrew environment service |
| `libkaihen/` | Homebrew API and JIT support |
| `common/` | Shared code and protocol definitions |
| `ounce-devkit` | Development toolkit for building homebrew |

## Supported Platforms

- Nintendo Switch 2.

kaiHEN is a separate project from Atmosphère and is not a Nintendo Switch 1 custom firmware release.

## Compatibility Information

The publicly documented compatibility status identifies:

| Item | Details |
|---|---|
| Project | kaiHEN |
| Identified build | 20261114d |
| Target platform | Nintendo Switch 2 |
| Firmware compatibility reported | 23.0.1 or earlier |
| Firmware 23.5.0 | Not supported by the identified build |
| Homebrew format | NRO |
| Development library | libkaihen |
| Development toolkit | ounce-devkit |
| Project status | Experimental / work in progress |

Compatibility depends on the separate acquisition method and the console firmware. The project does not provide a universal persistent installation method.

## Technical Specifications

| Specification | Details |
|---|---|
| Project name | kaiHEN |
| Repository | ouncebrew/kaihen |
| Developer | kurumuz / ouncebrew |
| Identified build | 20261114d |
| Platform | Nintendo Switch 2 |
| Project category | Homebrew enabler / minimal CFW |
| Main implementation | C and C++ |
| Homebrew loader | nx-hbloader |
| Homebrew menu | nx-hbmenu |
| Application format | NRO |
| JIT support | Yes |
| License | GPL-2.0-only with documented exemption |
| libkaihen license | ISC |

## Installation Guide

1. Check the console firmware against the compatibility information published by the project.
2. Review the official kaiHEN repository and its current development documentation.
3. Review the separate acquisition-tool documentation for the supported environment.
4. Obtain the project files from the official repository.
5. Use the matching `ounce-devkit` package if building applications or compiling the project from source.
6. Follow the repository's build instructions when compiling the components.
7. Start HEN through a compatible acquisition environment.
8. Open a native Switch 2 game while holding the R button to start the homebrew loader.
9. On subsequent launches, the documented behavior directs the launch to hbmenu.

The acquisition environment is separate from kaiHEN itself. The exact procedure and compatibility depend on the selected entry point.

## FAQ

### What is kaiHEN?

kaiHEN is an experimental homebrew environment and minimal custom firmware for Nintendo Switch 2.

### Does kaiHEN support NRO applications?

Yes. Its RO service maps NRO applications into client processes and provides JIT functionality.

### What happens when I hold R while opening a game?

The documented startup behavior launches the homebrew loader when a native game is opened while holding R. Subsequent launches open hbmenu.

### Can Switch 1 homebrew run on Switch 2?

Compatible applications using libnx and OpenGL or Vulkan can be rebuilt for Switch 2 using the project's development environment. This is a recompilation workflow, not automatic compatibility for every existing application.

### What is libkaihen?

libkaihen is the project's homebrew API, which includes additional JIT support.

### Does kaiHEN include a file manager?

The release packaging documented by the project includes OunceShell, a file manager with an FTP server.

### Is kaiHEN the same as Atmosphère?

No. Atmosphère targets the original Nintendo Switch, while kaiHEN is a separate experimental project targeting Switch 2.

### Where can I find the source code?

The source code and project documentation are available in the official ouncebrew GitHub repository.

## SEO Keywords

kaiHEN, Nintendo Switch 2 homebrew, Switch 2 CFW, Switch 2 homebrew environment, kaiHEN download, kaiHEN 20261114d, libkaihen, ounce-devkit, NRO loader, Switch 2 homebrew loader, Switch 2 development, OunceShell, JIT homebrew, Nintendo Switch 2 custom firmware

<div align="center">

---

**kaiHEN** · Nintendo Switch 2 Homebrew Environment

[Official GitHub Repository](https://github.com/ouncebrew/kaihen)

</div>
