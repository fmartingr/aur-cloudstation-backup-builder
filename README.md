# AUR Synology CloudStation Backup Builder

[![AUR CloudStation Drive](https://img.shields.io/badge/AUR-cloudstation--backup-green.svg)](https://aur.archlinux.org/packages/cloudstation-backup/)

Simple script to generate the AUR builds for the CloudStation Backup software by synology.

## Usage

```
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/python3 build.py <version> <release_number>
```

This will generate a new folder in the builds folder with the _PKGBUILD_ and _.SRCINFO_ files which are the required files to create an AUR package.