# Learning Nix Flakes

## Setup flakes and inititalize first flake

```bash
    ➜  pers mkdir -p nix-flake-1
    ➜  pers cd nix-flake-1
    ➜  nix-flake-1 nix flake init
    error: experimental Nix feature 'nix-command' is disabled; use '--extra-experimental-features nix-command' to override
    ➜  nix-flake-1 nix flake init --extra-experimental-features nix-command
    error: experimental Nix feature 'flakes' is disabled; use '--extra-experimental-features flakes' to override

    ➜  nix-flake-1 nix flake init --extra-experimental-features flakes --extra-experimental-features nix-command
    wrote: /home/hrutvik_/pers/nix-flake-1/flake.nix
    ➜  nix-flake-1 ls
    flake.nix

```
