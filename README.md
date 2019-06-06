# Ignite
An extendable shell framework for task automation

## Simple Setup
1. Configure execution of Ignite
    - EITHER add this directory to your `$PATH`
    ```
    echo "export PATH=\"$(pwd):$PATH\"" >> .zshrc
    ```
    - OR Create a symbolic link to `ignite` to a directory that is in your `$PATH`
2. (Optional) Set up autocomplete
    - Add `source <path_to_clone>/autocomplete_ignite` to your chosen shell profile, eg
    ```
    echo "source $(pwd)/autocomplete_ignite" >> .zshrc
    ```
