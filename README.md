# [CWTools-VSCode: Paradox Language Services](https://marketplace.visualstudio.com/items/tboby.cwtools-vscode)

**Paradox Language Features for Visual Studio Code**

## Disclaimer

This extension is still in preview, it may not work, it may stop working at any time.
**Make backups of your mod files.**

## Features

* Immediate highlighting of syntax errors
* Autocomplete while you type, providing descriptions when available
* A wide range of validators for common, interface, and events, checking
  * That required localisation keys are defined
  * Existence of effects/triggers/modifiers
  * Scope context for used effects/triggers/modifiers
  * Usage of scripted effects/triggers
  * Correct entries for weights/AI_chance/etc
  * That event\_targets are saved before they're used
  * That referenced sprites and graphics files exist
  * and a number of other specific validators
* "Code actions" to generate .yml for missing localisation
* Tooltips providing effect documentation

### Completion

![Completion](./docs/completion.gif)

### Tooltips

![Tooltips](./docs/tooltips.gif)

### Scope tooltips

![Scope tooltips](./docs/scopetooltip.gif)

### Scope errors

![Scope ](./docs/scopeerror.gif)

### Localisation error

![Localisation error](./docs/localisationerror.gif)

### Go to definition

![Go to definition](./docs/gotodef.gif)

### Find all references

![Find all references](./docs/findallrefs.gif)

## Usage

1. Install this extension
2. If on linux, possibly follow [these instructions](https://code.visualstudio.com/docs/setup/linux#_error-enospc)
3. If on linux, install libcurl3
4. Either open your mod folder directly
5. or open the Stellaris folder containing your mods. This can be one of:
    * "C:\Users\name\Paradox Interactive\Stellaris"
    * "C:\Program Files(x86)\Steam\steamapps\common\Stellaris"

    or on linux
    * "/home/name/.local/share/Paradox Interactive/Stellars"
    * "/home/name/.steam/steam/steamapps/common/Stellaris"
6. Edit files and watch syntax errors show up when you make mistakes
7. Wait up to a minute for the extension to scan all your mods and find all errors
