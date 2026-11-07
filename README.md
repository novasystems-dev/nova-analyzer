# Nova-Analyzer — Official Language Server & IDE Engine for Nova

> **Full Language Server Protocol (LSP) Support | Real-Time Type Hover | Semantic Highlighting | SMT Invariant Verification**

Nova-Analyzer is the official IDE engine for the **Nova Systems Programming Language**, modeled after `rust-analyzer` and `gopls`.

---

## Supported IDEs & Editors

- **Visual Studio Code**: Native extension with full syntax, diagnostics, and hover types.
- **Neovim**: Standard LSP configuration via `nvim-lspconfig`.
- **Helix**: Out-of-the-box language support.
- **Emacs**: `eglot` and `lsp-mode` integration.

---

## Features

- Real-time SMT refinement proof status on hover.
- Perceus in-place reuse diagnostics.
- Tree-sitter AST parsing integration.
- Go to definition, find references, and symbol renaming.
- Automated formatting via `nova-fmt` protocol.

---

## License

PolyForm Noncommercial License 1.0.0. Copyright (c) 2026 Fyew999 (Nova Systems).
See [LICENSE](LICENSE) for details.
