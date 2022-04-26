A transpiler for Mindustry Logic.

Standardizes function calls, variable names, etc. Has a list of builtin functions and an extended instruction set, see [spec.md](spec.md) for more information.

You can use this to manage large projects and split your code into multiple files.

This project is a work in progress, more useful stuff coming soon™

Usage: node compiler/compile.js

You may want to use a path script for that

Features:

* [x] Functions
* [x] Extra instructions like throw, increment, and call
* [x] Stops you from writing silly code like `ubind "poly"`
* [x] `mlogx --info` for information about a command
* [ ] more functions
* [ ] more extra instructions
* [x] STATIC TYPE CHECKING(this took me several hours)
* [ ] become an npm package
* [ ] not always include all functions 