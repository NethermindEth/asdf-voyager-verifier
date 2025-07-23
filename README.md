# asdf-voyager-verifier

[![Build](https://github.com/your-username/asdf-voyager-verifier/workflows/Build/badge.svg)](https://github.com/your-username/asdf-voyager-verifier/actions)
[![GitHub license](https://img.shields.io/github/license/your-username/asdf-voyager-verifier?color=blue)](https://github.com/your-username/asdf-voyager-verifier/blob/main/LICENSE)

[Starknet Contract Verifier](https://github.com/NethermindEth/voyager-verifier) plugin for the [asdf version manager](https://asdf-vm.com).

The Starknet Contract Verifier (binary name: `voyager`) is a contract class verification tool that allows you to verify your Starknet classes on a block explorer.

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `cargo` - Rust's package manager (install via [rustup](https://rustup.rs/))

## Install

Plugin:

```shell
asdf plugin add voyager https://github.com/your-username/asdf-voyager-verifier.git
```

voyager:

```shell
# Show all installable versions
asdf list-all voyager

# Install latest stable version
asdf install voyager latest

# Install specific version
asdf install voyager 0.4.1

# Set a version globally (on your ~/.tool-versions file)
asdf global voyager latest

# Now voyager commands are available
voyager --version  # Shows: Starknet Contract Verifier 0.4.3
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/your-username/asdf-voyager-verifier/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [Your Name](https://github.com/your-username/)
