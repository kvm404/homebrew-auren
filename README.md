# Homebrew tap for Auren

[Auren](https://github.com/kvm404/Auren) is a voice assistant: say what you want, and it uses your computer.

On a Mac with Apple Silicon and macOS 14 or newer:

```sh
brew install kvm404/auren/auren-macos
auren setup
```

`auren setup` builds Auren's environment, asks for the permissions it needs and starts it. It needs Claude Code or Codex as its brain. `auren update` installs new versions.

## Installed 0.1.8 or older?

Until 0.1.8 the formula was called `auren`. Homebrew's trust doesn't follow a rename, so run this once, then update as usual:

```sh
brew trust --formula kvm404/auren/auren-macos
auren update
```

Homebrew moves the install over to `auren-macos` by itself.

The formula here is published by Auren's release workflow. Don't edit it by hand: change `packaging/homebrew/auren-macos.rb` in [kvm404/Auren](https://github.com/kvm404/Auren) instead.
