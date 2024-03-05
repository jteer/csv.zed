# Zed CSV

Syntax highlighting for CSV in [Zed](https://github.com/zed-industries/zed).

### Test locally

- Clone this repo
- Clone the tree-sitter-csv repo
- cd into the repo: `cd tree-sitter-csv`
- Build the WASM: `tree-sitter build-wasm`
- Rename the WASM file to `csv.wasm`
- Move the WASM file into `csv/grammars` (this repository)
- Move the `csv`repository to `~/Library/Application Support/Zed/extensions/installed`