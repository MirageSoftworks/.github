![Mirage Softworks — tools for Roblox developers](https://raw.githubusercontent.com/MirageSoftworks/.github/main/profile/assets/banner.svg)

# Mirage Softworks

Mirage is a set of tools for packaging and protecting Roblox games, written in Rust and Luau.

- **Game packer** shuffles every instance, nests them randomly under different names, and sets traps on attributes.
- **Virtualizer** obfuscates your Luau code. Use it on its own or together with the packer.
- **Analyzers** statically check scripts for references and network code.
- **Roblox IDE** (coming soon) starts you from a clean Rojo workspace with project templates.

Mirage reads a saved place, a Rojo project, or Script Sync folders and writes a separate build, so your source stays untouched. The same seed and inputs give the same output.

## Status

Under active development. Percentages are rough estimates for the current scope.

| Project | Progress | Notes |
| --- | --- | --- |
| [Mirage Engine](https://github.com/MirageSoftworks/engine) | ![Refining](https://us-central1-progress-markdown.cloudfunctions.net/progress/90?barColor=8b5cf6&label=Refining) | Game packer and virtualizer. Adding support for more game formats. |
| [Analyzers](https://github.com/MirageSoftworks/analyzers) | ![Expanding](https://us-central1-progress-markdown.cloudfunctions.net/progress/70?barColor=8b5cf6&label=Expanding) | Static Luau reference and network analysis. |
| [Integrations](https://github.com/MirageSoftworks/integrations) | ![Developing](https://us-central1-progress-markdown.cloudfunctions.net/progress/50?barColor=8b5cf6&label=Developing) | Dashboard, VS Code extension, Studio plugin. Backend work still missing in places. |
| [Contracts](https://github.com/MirageSoftworks/contracts) | ![Expanding](https://us-central1-progress-markdown.cloudfunctions.net/progress/60?barColor=8b5cf6&label=Expanding) | Versioned schemas for stable engine and integration interfaces. |
| [Website](https://github.com/MirageSoftworks/website) | ![Building](https://us-central1-progress-markdown.cloudfunctions.net/progress/40?barColor=8b5cf6&label=Building) | Docs site. Foundation done, content still to write. |
| [Roblox IDE](https://github.com/lates-codrin/cline) *(separate repo)* | ![Early stage](https://us-central1-progress-markdown.cloudfunctions.net/progress/20?barColor=8b5cf6&label=Early%20stage) | Early Cline fork. Visual scripting doesn't work yet, and it isn't connected to the packer or virtualizer. |

Planned: an authentication service.
