# Zsh-plugin-rust

A simple Zsh plugin providing convenient aliases for working with Rust's Cargo, Rustc, and Rustup tools.

## Features

- Short aliases for common Cargo commands
- Aliases for Rustc and Rustup utilities
- Easy installation and usage

## Aliases

| Alias   | Command                        | Description                       |
|---------|-------------------------------|-----------------------------------|
| `c`     | `cargo`                       | Run Cargo                         |
| `cr`    | `cargo run`                   | Run project                       |
| `ccr`   | `cargo clean && cargo run`    | Clean and run project             |
| `ccl`   | `cargo clean`                 | Clean project                     |
| `ci`    | `cargo install`               | Install a Cargo package           |
| `ca`    | `cargo add`                   | Add a dependency                  |
| `cver`  | `cargo --version`             | Show Cargo version                |
| `rc`    | `rustc`                       | Run Rust compiler                 |
| `rcve`  | `rustc --version`             | Show Rustc version                |
| `ru`    | `rustup`                      | Run Rustup                        |
| `ruver` | `rustup --version`            | Show Rustup version               |
| `rui`   | `rustup install`              | Install Rust toolchain            |
| `ruc`   | `rustup component add`        | Add Rustup component              |
| `rus`   | `rustup show`                 | Show Rustup info                  |
| `rul`   | `rustup list`                 | List Rustup toolchains/components |
| `rct`   | `rustc --target`              | Compile for target                |
| `rctls` | `rustc --target-list`         | List available targets            |
| `rcti`  | `rustc --target-install`      | Install target                    |
| `rctu`  | `rustc --target-uninstall`    | Uninstall target                  |
| `rctv`  | `rustc --version --verbose`   | Show verbose Rustc version        |

## Installation

You can also use this plugin in a plain Zsh setup without Oh My Zsh.

1. Clone the repository anywhere you like:

   ```bash
   git clone https://github.com/betterfetch/zsh-plugin-rust.git $DESTIATION
2. Add it to your ~/.zshrc
    ```bash 
    ...
    source ~/$DESTINATION/zsh-plugin-rust.plugin.zsh
    ```
3. Reload your shell
    ```bash 
    exec zsh
    ```

## Installation with Oh My Zsh

1. Clone or copy the plugin into your Oh My Zsh custom plugins directory:
    ```bash
   git clone https://github.com/betterfetch/zsh-plugin-rust.git $ZSH_CUSTOM/plugins/zsh-plugin-rust
2. Add the plugin to ~/.zshrc
    ```bash
    plugins=(... zsh-plugin-rust)
    ```
3. Reload your shell
    ```bash
    exec zsh
    ```    
