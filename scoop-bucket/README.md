# Homebrew/Scoop bucket for Maury Markowitz projects

This repository provides Homebrew formulae and Scoop manifests for unofficial software packages.

## Scoop bucket installation

    scoop bucket add maurymarkowitz https://github.com/maurymarkowitz/scoop-bucket

## Current manifests

- `onec.json`
  - OpenNEC antenna simulator
  - version 1.1.3
  - homepage: https://github.com/maurymarkowitz/OpenNEC
  - binary package: `onec-windows-x86_64.zip`

- `retrojoss.json`
  - RetroJOSS interpreter for old JOSS programs
  - version 1.1.0
  - homepage: https://github.com/maurymarkowitz/RetroJOSS
  - binary package: `retrojoss-windows-x86_64.zip`

- `retrofocal.json`
  - RetroFOCAL interpreter for classic FOCAL programs
  - version 1.1.4
  - homepage: https://github.com/maurymarkowitz/RetroFOCAL
  - expected binary package: `retrofocal-windows-x86_64.zip`
  - note: upstream release currently contains source only; this manifest has a placeholder checksum and should be updated once a Windows release asset is available.

- `retrobasic.json`
  - RetroBASIC interpreter for classic BASIC programs
  - version 2.1.2
  - homepage: https://github.com/maurymarkowitz/RetroBASIC
  - expected binary package: `retrobasic-windows-x86_64.zip`
  - note: upstream release currently contains source only; this manifest has a placeholder checksum and should be updated once a Windows release asset is available.

## Install

    scoop install retrofocal
    scoop install retrobasic

## Run

    retrofocal --help
    retrobasic --help

## Uninstall

    scoop uninstall retrofocal
    scoop uninstall retrobasic

1. Add the bucket:

```powershell
scoop bucket add maurymarkowitz https://github.com/maurymarkowitz/scoop-bucket
```

2. Install RetroFOCAL:

```powershell
scoop install retrofocal
```

3. Install RetroBASIC:

```powershell
scoop install retrobasic
```

4. Run:

```powershell
retrofocal --help
retrobasic --help
```

5. Uninstall:

```powershell
scoop uninstall retrofocal
scoop uninstall retrobasic
```

