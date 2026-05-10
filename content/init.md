+++
date = 2025-03-03
update_date = 2026-05-10
title = "[Edition 2024] Bash oneliner for fresh `cargo init` project"

[taxonomies]
tags = ["rust", "toml", "editorconfig", "clippy"]
+++

### Content

- `.editorconfig`
- `taplo.toml` (TOML-formatter config)
- `rustfmt.toml`
- `clippy.toml`
- `lints.toml` (template for `[workspace.lints]` in your `Cargo.toml`)

### Oneliner

> **Hint**: run it directly:
>
> - `curl -fsSL https://awnion.github.io/init.sh | bash`
>
> Or pipe your clipboard into `bash` (after copying the script below):
>
> - MacOS: `pbpaste | bash`
> - X11: `xclip -o -selection clipboard | bash`
> - Wayland: `wl-paste | bash`
> - Windows: `powershell.exe -c Get-Clipboard | bash`

{{ load_file(path="static/init.sh", language="bash") }}

