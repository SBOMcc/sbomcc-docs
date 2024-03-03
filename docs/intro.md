---
sidebar_position: 1
---

# Getting Started

Let's get started with **sbom.cc**, _SBOM Parsing for Humans_.

## Parse a local SBOM file

Get started by parsing a local SBOM file.

### What you'll need

sbom.cc runs on modern versions of Linux and macOS.

Tested on:

- macOS 14 (Apple M1/M2)
- Ubuntu 22.04.02 (Linux 5.15)

## Install sbom.cc

Get the latest version of sbom.cc from our releases and unzip it.

Here's an example using Ubuntu.

```bash
wget https://github.com/SBOMcc/sbomcc/releases/download/0.0.1/sbomcc-0.0.1-linux-x64.zip
unzip sbomcc-0.0.1-linux-x64.zip
cd sbomcc-0.0.1/bin
```

## Parse a local SBOM

```bash
./sbomcc -f spdx.json
```
