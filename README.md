# dotfiles

## Installation

Follow the steps below to install these configurations on your system.

### Step 1: Clone the repository

```bash
git clone git@github.com:thaishdz/dotfiles.git ~/.dotfiles
```

### Step 2 : Install

```bash
./install
```

---

### Adding additional configs to `install.conf.yaml`

```yaml
- link:
    ~/.zshrc: /zsh/zshrc
```

#### Step 1: Crea un enlace simbólico donde

- `~/.zshrc` es la ubicación de destino donde el archivo de configuración debe estar en tu sistema (es tu home).

- `/zsh/zshrc` es el nombre del archivo en tu repositorio de dotfiles.

#### Step 2: Commit and push your changes

```bash

git add .
git commit -m "Add XXXX"
git push
```
