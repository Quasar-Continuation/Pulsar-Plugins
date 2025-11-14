# 🔌 Pulsar Plugins

This repository contains official and community plugin projects for the **Pulsar** ecosystem.

Plugins extend the functionality of the Pulsar client and server by using shared code from [`Pulsar.Common`](https://github.com/Quasar-Continuation/Poopsar/tree/main/Pulsar.Common).

---

## Navigation
[Setup](#setup) <br>
[Updating](#updating) <br>
[Docs](/Docs/README.MD)
---

## ⚙️ Setup Instructions

# setup

### 🧩 1. Clone the repository with submodules

`Pulsar.Common` (the Poopsar repository) is required for all plugin builds.

Recommended (one-step):

```bash
git clone --recurse-submodules https://github.com/Quasar-Continuation/Pulsar-Plugins.git
```

If you already cloned without submodules, initialize them with:

```bash
git submodule update --init --recursive
```

If the above command does not create the expected folders (for example `External/Poopsar`), this repository includes helper scripts that will attempt to initialize submodules and fall back to cloning the configured URLs.

Windows (PowerShell):

```powershell
pwsh.exe .\scripts\init-submodules.ps1
```

macOS / Linux / Git Bash:

```bash
./scripts/init-submodules.sh
```

### 🔄 Updating to the Latest Pulsar.Common

# updating

To update the Poopsar submodule to the latest upstream changes:

```bash
git submodule update --remote --merge
```

### Plugin documentation

Plugin documentation can be found in: [Docs](/Docs/README.MD)
