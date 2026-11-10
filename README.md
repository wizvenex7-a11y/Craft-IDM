
<p align="center">
  <img src="assets/brand/craft-idm-logo.png" alt="Craft-IDM" width="220">
</p>

<p align="center">
  <img src="assets/app-icon.png" width="128" height="128" alt="Craft-IDM application icon">
</p>

<h1 align="center">Craft-IDM</h1>

<p align="center">
  <b>A modern download manager built with Go.</b>
  <br>
  A clean and convenient way to organize and manage your downloads.
</p>

<p align="center">
  <img alt="Language: Go" src="https://img.shields.io/badge/Language-Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="Platform: Windows" src="https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/License-TBD-gray?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/Status-Development-orange?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/wizvenex7-a11y/Craft-IDM/releases">
    <img src="https://img.shields.io/badge/Download-Craft--IDM-2563EB?style=for-the-badge&logo=windows&logoColor=white" height="40">
  </a>
</p>

<p align="center">
  <a href="#features">Features</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#building-from-source">Build</a> ·
  <a href="#downloads">Downloads</a> ·
  <a href="#license">License</a>
</p>

---

## About Craft-IDM

**Craft-IDM** is a Go-based download manager project designed to provide a convenient experience for downloading and managing files.

The project aims to combine a modern interface with a lightweight application and straightforward download management.

## Features

- **Download management** — Manage your downloads from one application.
- **Modern interface** — A clean and user-friendly application design.
- **Go powered** — Built using the Go programming language.
- **Windows support** — Build and run the Windows application.
- **Open source** — Explore, modify and contribute to the project.

> Note: Features listed here describe the project's intended presentation. Update them to match the implemented functionality.

## Screenshots

<p align="center">
  <img src="docs/images/main-window.png" alt="Craft-IDM main interface" width="100%">
  <br>
  <sub>Craft-IDM main application interface.</sub>
</p>

<p align="center">
  <img src="docs/images/download-manager.png" alt="Craft-IDM download manager" width="100%">
  <br>
  <sub>Download management interface.</sub>
</p>

## Installation

### Download the application

1. Open the [Craft-IDM Releases](https://github.com/wizvenex7-a11y/Craft-IDM/releases) page.
2. Download the latest Windows release when available.
3. Extract the archive if necessary.
4. Launch `Craft-IDM.exe`.

### System requirements

- Windows (target platform).
- A compatible Windows 64-bit system for the x64 build.

## Building from source

### Requirements

- [Go](https://go.dev/dl/)
- Git

### Clone the repository

```bash
git clone https://github.com/wizvenex7-a11y/Craft-IDM.git
cd Craft-IDM
```

### Build for Windows

```bash
go build -o Craft-IDM.exe .
```

### Run from source

```bash
go run .
```

## Downloads

Get the latest version from GitHub Releases.

<p align="center">
  <a href="https://github.com/wizvenex7-a11y/Craft-IDM/releases">
    <img src="https://img.shields.io/badge/Download-Latest_Release-2563EB?style=for-the-badge&logo=github" alt="Download latest release">
  </a>
</p>

| Platform | Architecture | Status |
|---|---|---|
| Windows | x64 | Release pending |
| Windows | ARM64 | Not confirmed |
| Linux | x64 | Not confirmed |
| macOS | ARM64 / x64 | Not confirmed |

## Project Structure

```text
Craft-IDM/
├── assets/
│   ├── brand/
│   └── app-icon/
├── docs/
│   └── images/
├── go.mod
├── go.sum
├── main.go
└── README.md
```

*Example suggested structure; adapt it to the actual source tree.*

## Contributing

Contributions, suggestions and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

## License

A license has not yet been specified. Add a `LICENSE` file before distributing the project under an open-source license.

---

<p align="center">
  <b>Craft-IDM</b>
  <br>
  Built with Go ❤️
  <br><br>
  <a href="https://github.com/wizvenex7-a11y/Craft-IDM">
    GitHub Repository
  </a>
</p>
