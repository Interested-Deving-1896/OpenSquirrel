[update-readmes]   Mode: rewrite — migrating to template structure...
# OpenSquirrel

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/OpenSquirrel)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/OpenSquirrel.git
cd OpenSquirrel
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


Config lives at `~/.opensquirrel/config.toml`. Defines runtimes, models, MCP servers, machines, themes, and settings.

State is persisted at `~/.opensquirrel/state.json` (agents, transcripts, scroll positions).

## CI

<!-- AI:start:ci -->
- **`build.yml`**: Verifies that the project builds successfully using Rust's `cargo build`. Runs on all pushes and pull requests. No secrets required.

- **`test.yml`**: Executes the test suite using `cargo test` to ensure code correctness. Runs on all pushes and pull requests. No secrets required.

- **`lint.yml`**: Checks code formatting and adherence to Rust standards using `cargo fmt --check` and `cargo clippy`. Runs on all pushes and pull requests. No secrets required.

- **`release.yml`**: Builds and publishes a release artifact when a new GitHub release is created. Requires the `CRATES_IO_TOKEN` secret for publishing to crates.io.

- **`docs.yml`**: Generates and deploys documentation to GitHub Pages using `cargo doc`. Runs on pushes to the `main` branch. No secrets required.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/OpenSquirrel`](https://github.com/Interested-Deving-1896/OpenSquirrel) and mirrored through:

```
Interested-Deving-1896/OpenSquirrel  ──►  OpenOS-Project-OSP/OpenSquirrel  ──►  OpenOS-Project-Ecosystem-OOC/OpenSquirrel
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/OpenSquirrel/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
