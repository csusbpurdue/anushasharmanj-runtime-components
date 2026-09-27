# runtime_components

My personal configuration files for the terminal, editor,
debugger, and git, plus  script that installs them.

## contents

| File         | What it configures                                   |
|--------------|------------------------------------------------------|
| `.bashrc`    | Bash: history, colored prompt with git branch, aliases |
| `.zshrc`     | Zsh (the default shell on macOS)                     |
| `.vimrc`     | Vim editor settings                                  |
| `.gdbinit`   | GDB debugger settings                                |
| `.gitconfig` | Git aliases and defaults (no name/email)             |
| `install.sh` | Copies the files above into my home directory        |

## Installation

```bash
git clone https://github.com/<your-username>/runtime_components.git ~/runtime_components
cd ~/runtime_components
./install.sh --dry-run   # preview what will change
./install.sh             # install for real
```

Then open a new terminal window


## Notes

- After editing a file in this repo, run `./install.sh` again to apply it.

## Author

Anusha Sharma, Purdue University
