{% if page.url == "/" %}
  <div class="landing_page_banner">
    <img src="./cwtools_logo.png" class="logo">
    <h1> CW Tools </h1>
    <h3> Fun, productive, cleaner modding </h3>
    <h3 align="center">
      <a href="https://herrx2000.github.io/cwtools-vscode/getting-started" class="Button highlighted" style="padding-right:50px">Get started</a>
      <a href="https://marketplace.visualstudio.com/items?itemName=tboby.cwtools-vscode" class="Button"  target="_blank">Download ›</a>
    </h3>
  </div>
  <div style="margin-top:80px">
  </div>
{% endif %}

## Features

* Immediate highlighting of syntax errors
* Autocomplete while you type, providing descriptions when available
* Tooltips on hover showing:
  * Related localisation
  * Documentation for that element
  * Scope context at that position
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

### Completion

![Completion](./completion.gif)

### Tooltips

![Tooltips](./tooltips.gif)

### Scope tooltips

![Scope tooltips](./scopetooltip.gif)

### Scope errors

![Scope ](./scopeerror.gif)

### Localisation error

![Localisation error](./localisationerror.gif)

### Go to definition

![Go to definition](./gotodef.gif)

### Find all references

![Find all references](./findallrefs.png)

