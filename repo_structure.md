## Project Structure

### `src/`
The core TypeScript source code.

### `extensions/`
Built-in extensions, including:
- Git
- Markdown
- Copilot Chat

**Reference:** `package.json` — lines 27

### `build/`
Configuration for the build pipeline, including:
- Gulp
- Rspack
- Vite

**Reference:** `package.json` — lines 56–76

### `cli/`
The Rust-based command-line interface.

**Reference:** `product.json` — line 16

### `remote/`
Configuration and dependencies for the Remote Extension Host (REH) and web server.

**Reference:** `remote/package.json` — lines 1–5
