![Mirage Softworks — tools for Roblox developers](https://raw.githubusercontent.com/MirageSoftworks/.github/main/profile/assets/banner.svg)

# Mirage Softworks

**Build with clarity. Ship something different.**

We make tools for the worlds you build. **Mirage** is a Rust + Luau build tool for Roblox creators, bringing project analysis, build transformations, and editor integrations into one workflow.

Start with a saved place, a Rojo project, or native Script Sync folders. Keep your editable source separate from generated output, and reproduce builds with a chosen seed and matching inputs.

| Build | Inspect | Work your way |
| --- | --- | --- |
| Transform supported project inputs into separate output. | Analyze references and network-related code statically. | Use the dashboard, VS Code tools, and Studio tools. |

From inspecting references to generating a fresh build, the goal is simple: useful tooling that fits the way Roblox developers already work.

## Project progress

Mirage is under active development across several repositories. These are rough estimates of functional completion toward the current scope, not measures of time spent or promises of release readiness.

| Project | Progress | Focus |
| --- | --- | --- |
| [Mirage Engine](https://github.com/MirageSoftworks/engine) | ![Refining](https://us-central1-progress-markdown.cloudfunctions.net/progress/90?barColor=8b5cf6&label=Refining) | The obfuscator and game packer are implemented. Current work improves them, including support for more game formats; further hardening and release readiness remain. |
| [Analyzers](https://github.com/MirageSoftworks/analyzers) | ![Expanding](https://us-central1-progress-markdown.cloudfunctions.net/progress/70?barColor=8b5cf6&label=Expanding) | Independent static Luau reference and networking analysis. Core analysis is in place and continues to expand. |
| [Integrations](https://github.com/MirageSoftworks/integrations) | ![Developing](https://us-central1-progress-markdown.cloudfunctions.net/progress/50?barColor=8b5cf6&label=Developing) | Dashboard, VS Code extension, and Roblox Studio companion. UI and integration work is underway; some areas still need deeper product/backend integration. |
| [Contracts](https://github.com/MirageSoftworks/contracts) | ![Expanding](https://us-central1-progress-markdown.cloudfunctions.net/progress/60?barColor=8b5cf6&label=Expanding) | Versioned schemas and fixtures for selected engine and integration interfaces. Coverage is intentionally limited to stable, observed contracts. |
| [Website](https://github.com/MirageSoftworks/website) | ![Building](https://us-central1-progress-markdown.cloudfunctions.net/progress/40?barColor=8b5cf6&label=Building) | Product documentation site. The documentation foundation is underway; broader content and launch polish remain. |
| [Roblox-focused IDE](https://github.com/lates-codrin/cline) *(separate repository)* | ![Early stage](https://us-central1-progress-markdown.cloudfunctions.net/progress/20?barColor=8b5cf6&label=Early%20stage) | Currently an early-stage Cline fork. The obfuscator and packer are not integrated; visual scripting is not functional, and many features are UI without backend behavior. |

These estimates describe current implementation, not the entire long-term vision. The IDE is being developed outside this organization. Authentication and other planned services remain part of the broader roadmap.
