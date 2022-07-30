# gmxenv

gromacs version manager

# Install

Clone this repository.

```sh
git clone https://github.com/uga-rosa/gmxenv.git ~/.gmxenv
```

Add the following into your .bashrc

```sh
export PATH="$HOME/.gmxenv/bin:$HOME/.gmxenv/shims:$PATH"
```

# Usage

```sh
gmxenv [subcommand] [arguments]
```

## subcommands

- install [version]

Install that version of gromacs.

- switch [version]

Switch that version.

- versions

Show now installed versions of gromacs.

- help

Show help message.
