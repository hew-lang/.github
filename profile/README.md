# Hew

Hew is a statically typed, actor-oriented programming language for concurrent and distributed systems. The compiler produces native code through LLVM. Hew is under active development; see the [current release](https://github.com/hew-lang/hew/releases) and [documentation](https://hew.sh/docs/) for supported behaviour.

## Get Started

- [Getting started](https://hew.sh/docs/getting-started/) — Install Hew, set up an editor, and run your first program
- [Learn Hew](https://hew.sh/learn/) — Interactive lessons
- [hew.run](https://hew.run) — Online playground
- [Language specification](https://github.com/hew-lang/hew/blob/main/docs/specs/HEW-SPEC-2026.md) — Edition 2026; the language edition is separate from the compiler version

### Install

```bash
brew install hew-lang/hew/hew
```

### Editor Support

- **VS Code** — [Hew Language](https://marketplace.visualstudio.com/items?itemName=hew-lang.hew-lang) extension (syntax highlighting + LSP)
- **Vim / Neovim** — [vim-hew](https://github.com/hew-lang/vim-hew) syntax plugin
- **Tree-sitter** — [tree-sitter-hew](https://github.com/hew-lang/tree-sitter-hew) grammar for Neovim, Helix, Zed, and other tree-sitter editors

## Repositories

| Repository | Description |
|---|---|
| [hew](https://github.com/hew-lang/hew) | Compiler, LSP server, and language toolchain |
| [tree-sitter-hew](https://github.com/hew-lang/tree-sitter-hew) | Editor grammar mirroring the compiler's lexer and parser |
| [vscode-hew](https://github.com/hew-lang/vscode-hew) | VS Code extension with syntax highlighting and LSP |
| [vim-hew](https://github.com/hew-lang/vim-hew) | Vim/Neovim syntax highlighting |
| [hew.sh](https://github.com/hew-lang/hew.sh) | Language website and documentation |
| [homebrew-hew](https://github.com/hew-lang/homebrew-hew) | Homebrew tap for macOS/Linux installation |
| [Examples](https://github.com/hew-lang/hew/tree/main/examples) | Example programs and patterns |

## Community and contributions

Ask questions and discuss ideas in [GitHub Discussions](https://github.com/orgs/hew-lang/discussions). For a reproducible problem, use the [bug report form](https://hew.sh/bugs/). Start with the [compiler contribution guide](https://github.com/hew-lang/hew/blob/main/CONTRIBUTING.md) before changing the toolchain.

## License

The compiler is dual-licensed under [MIT or Apache-2.0](https://github.com/hew-lang/hew#license). See each repository for its licence terms.
