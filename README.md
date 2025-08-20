# Work in progress. Not yet published to marketplace.

# Raven Hydrological Model Input Files - Syntax Highlighting Extension

This extension provides syntax highlighting for Raven hydrological model input files, converted directly the from Notepad++ [User Defined Language](https://raven.uwaterloo.ca/files/RavenInputFilesUDL.xml) (UDL) files. 

## Supported File Extensions

- `.rvi` - Raven input files
- `.rvt` - Raven time series files  
- `.rvc` - Raven initial conditions files
- `.rvh` - Raven hydrologic response unit files
- `.rvp` - Raven parameter files

## Features

- **Syntax Highlighting**: Exact keyword highlighting as defined in original Notepad++ UDL files
- **Code Folding**: Automatic folding for major sections (`:SubBasins`, `:HRUs`, etc.)
- **Comments**: Support for `#` line comments and file header comments (`:FileType`, `:WrittenBy`, `:CreationDate`)
- **Themes**: Light and dark theme variants with exact color matching from original UDL files

## Installation

### VS Code

#### Development Installation

1. **Copy to extensions directory**:
   ```bash
   # Windows
   cp -r raven-vscode %USERPROFILE%\.vscode\extensions\raven-vscode
   
   # macOS/Linux
   cp -r raven-vscode ~/.vscode/extensions/raven-vscode
   ```

2. **Reload VS Code**:
   - Restart VS Code, or
   - Run "Developer: Reload Window" from Command Palette (`Ctrl+Shift+P`/`Cmd+Shift+P`)

### Positron

Positron uses the same extension format as VS Code, so installation is identical:

### Development Installation

1. **Copy to Positron extensions directory**:
   ```bash
   # Windows
   cp -r raven-vscode %USERPROFILE%\.positron\extensions\raven-vscode
   
   # macOS/Linux  
   cp -r raven-vscode ~/.positron/extensions/raven-vscode
   ```

2. **Reload Positron**:
   - Restart Positron, or
   - Run "Developer: Reload Window" from Command Palette

