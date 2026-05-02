# Hew

**A new language for resilient services.**

Hew is a high-performance, network-native, machine-code compiled language for building long-lived services. Actor isolation, supervision trees, and wire contracts — compiled to native code through LLVM.

## Get Started

- [hew.sh](https://hew.sh) — Language website and documentation
- [hew.run](https://hew.run) — Online playground
- [HEW-SPEC.md](https://github.com/hew-lang/hew/blob/main/docs/specs/HEW-SPEC.md) — Language specification (v0.3.0)

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
| [tree-sitter-hew](https://github.com/hew-lang/tree-sitter-hew) | Tree-sitter grammar (authority syntax definition) |
| [vscode-hew](https://github.com/hew-lang/vscode-hew) | VS Code extension with syntax highlighting and LSP |
| [vim-hew](https://github.com/hew-lang/vim-hew) | Vim/Neovim syntax highlighting |
| [hew.sh](https://github.com/hew-lang/hew.sh) | Language website and documentation |
| [hew.run](https://github.com/hew-lang/hew.run) | Online playground |
| [homebrew-hew](https://github.com/hew-lang/homebrew-hew) | Homebrew tap for macOS/Linux installation |
| [Examples](https://github.com/hew-lang/hew/tree/main/examples) | Example programs and patterns |

## Design

Hew is built around four pillars:

- **Actor Isolation** — Every actor owns its state. No shared memory, no data races. Compile-time capability checking ensures safety without runtime cost.
- **Supervision Trees** — Services crash — Hew expects it. Supervisors restart failed children with configurable strategies.
- **Structured Concurrency** — Tasks are scoped to their parent. Cleanup is automatic and deterministic.
- **Wire Contracts** — Network protocols are first-class types with schema evolution rules enforced at compile time.

## License

Apache 2.0
