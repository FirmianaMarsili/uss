
Provides syntax highlighting, Go To Definition (F12 & Ctrl+Click), IntelliSense, signature help, code formatting, real-time diagnostics, `#define` type alias recognition, and cross-file navigation for `.shader`, `.hlsl`, `.cginc`, `.compute` and more.

---

## Features

### Syntax Highlighting
- **16 independently customizable** token colors for ShaderLab + HLSL/CG
- Automatic struct name recognition and highlighting (collected from current file, #include chains, and sibling files)

### Navigation
- **Go To Definition (F12)** — Jump to functions, structs, fields, variables, parameters, macros
- **Ctrl+Click** — Hold Ctrl and click to navigate; hover shows underline hint
- **Find All References (Shift+F12)** — Find all usages of a symbol
- **#include recursive search** — Walk include chains layer by layer (configurable depth)
- **Sibling file search** — Search all shader files in the same directory (optional)
- **Member access resolution** — `output.positionWS` jumps to the corresponding struct field definition

### IntelliSense
- HLSL/CG built-in functions, types, semantics, keywords
- ShaderLab keywords and property types
- Unity URP/HDRP built-in functions and variables
