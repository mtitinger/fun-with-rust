# fun-with-rust

## Preliminary Rust Setup

* `apt install rustup`
* `rustup install stable`

## Building from command line

* `cargo build`

## Buidling and debugging in VSCode

### Extension

you need essentially [CodeLLDB|https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb] on top of rust support

### Using multi-root workspaces

example folders have been added to the parent vscode workspace, so that youcan launch code from the toplevel folder.
open the `examples.code-workspace` fime, and click on Open Workspace.
From that point on, you can select the debug configuration for either example: set a breakpoint, hit F5 and have fun! 

