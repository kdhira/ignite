# Ignite
_An extendable shell framework for task automation_

## Simple Setup
1. Install Ignite:
    1. `git checkout stable` (or `git checkout dev` for latest dev build)
    2. `./ignite setup install`
        - Add `--link-location <dir>` to the end if you want to install to a custom directory
2. (Optional) Set up autocomplete
    - Add `source <path_to_clone>/autocomplete_ignite` to your chosen shell profile, eg
    ```
    echo "source $(pwd)/autocomplete_ignite" >> .zshrc
    ```
