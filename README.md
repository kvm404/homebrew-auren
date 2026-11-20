# Homebrew tap for Auren

[Auren](https://github.com/kvm404/Auren) is a voice assistant: say what you want, and it uses your computer.

On a Mac with Apple Silicon and macOS 14 or newer:

```sh
brew install kvm404/auren/auren
auren setup
```

`auren setup` builds Auren's environment, asks for the permissions it needs and starts it. It needs Claude Code or Codex as its brain.

The formula here is published by Auren's release workflow. Don't edit it by hand: change `packaging/homebrew/auren.rb` in [kvm404/Auren](https://github.com/kvm404/Auren) instead.
