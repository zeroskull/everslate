<div align="center">

# Everslate

</div>

## Terminal ANSI 16

**Normal**

<table align="center">
<tr>
    <th>0</th>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th>4</th>
    <th>5</th>
    <th>6</th>
    <th>7</th>
</tr>
<tr>
    <td align="center"><img src="./assets/ansi-0.svg?v=1.11.1" width="64" alt="ansi-0 swatch"><br><code>#3F565E</code></td>
    <td align="center"><img src="./assets/ansi-1.svg?v=1.11.1" width="64" alt="ansi-1 swatch"><br><code>#CF7677</code></td>
    <td align="center"><img src="./assets/ansi-2.svg?v=1.11.1" width="64" alt="ansi-2 swatch"><br><code>#6E9E8B</code></td>
    <td align="center"><img src="./assets/ansi-3.svg?v=1.11.1" width="64" alt="ansi-3 swatch"><br><code>#B7875A</code></td>
    <td align="center"><img src="./assets/ansi-4.svg?v=1.11.1" width="64" alt="ansi-4 swatch"><br><code>#4196C7</code></td>
    <td align="center"><img src="./assets/ansi-5.svg?v=1.11.1" width="64" alt="ansi-5 swatch"><br><code>#9583B8</code></td>
    <td align="center"><img src="./assets/ansi-6.svg?v=1.11.1" width="64" alt="ansi-6 swatch"><br><code>#6997A7</code></td>
    <td align="center"><img src="./assets/ansi-7.svg?v=1.11.1" width="64" alt="ansi-7 swatch"><br><code>#EDE6D5</code></td>
</tr>
</table>

**Bright**

<table align="center">
<tr>
    <th>8</th>
    <th>9</th>
    <th>10</th>
    <th>11</th>
    <th>12</th>
    <th>13</th>
    <th>14</th>
    <th>15</th>
</tr>
<tr>
    <td align="center"><img src="./assets/ansi-8.svg?v=1.11.1" width="64" alt="ansi-8 swatch"><br><code>#91A2A8</code></td>
    <td align="center"><img src="./assets/ansi-9.svg?v=1.11.1" width="64" alt="ansi-9 swatch"><br><code>#FF918E</code></td>
    <td align="center"><img src="./assets/ansi-10.svg?v=1.11.1" width="64" alt="ansi-10 swatch"><br><code>#8BBE95</code></td>
    <td align="center"><img src="./assets/ansi-11.svg?v=1.11.1" width="64" alt="ansi-11 swatch"><br><code>#DBBC7F</code></td>
    <td align="center"><img src="./assets/ansi-12.svg?v=1.11.1" width="64" alt="ansi-12 swatch"><br><code>#7FBBB3</code></td>
    <td align="center"><img src="./assets/ansi-13.svg?v=1.11.1" width="64" alt="ansi-13 swatch"><br><code>#EAACC9</code></td>
    <td align="center"><img src="./assets/ansi-14.svg?v=1.11.1" width="64" alt="ansi-14 swatch"><br><code>#8BBACA</code></td>
    <td align="center"><img src="./assets/ansi-15.svg?v=1.11.1" width="64" alt="ansi-15 swatch"><br><code>#F8F5E5</code></td>
</tr>
</table>

### Terminal example

<div align="center">
<img src="./assets/terminal-example.png?v=1.11.1" width="680" alt="Everslate terminal example">
</div>


### VS Code

<img src="./assets/vscode.png?v=1.11.1" alt="VS Code with the Everslate color theme" width="860">

**VS Code**: download [`vscode/everslate-1.11.1.vsix`](./vscode/everslate-1.11.1.vsix) and install it via the Extensions view → ⋯ → **Install from VSIX…**, or from the command line:

```
code --install-extension vscode/everslate-1.11.1.vsix
```

Then pick the theme with **Ctrl+K Ctrl+T**.

### Other terminals

**iTerm2** (and anything that imports `.itermcolors`): Settings → Profiles → Colors → Color Presets → Import… and pick [`terminal/iterm2/everslate.itermcolors`](./terminal/iterm2/everslate.itermcolors). Many other terminals and tools accept this format directly or through converters.

**Ghostty**: place [`terminal/ghostty/everslate`](./terminal/ghostty/everslate) in `~/.config/ghostty/themes/` and set `theme = "everslate"` in your Ghostty config (or pick it in the theme picker). Applies to new windows.

**Konsole**: copy [`terminal/konsole/Everslate.colorscheme`](./terminal/konsole/Everslate.colorscheme) into `~/.local/share/konsole/`, then select Everslate under Settings → Edit Current Profile → Appearance.

**Xfce4-terminal**: copy [`terminal/xfce4-terminal/everslate.theme`](./terminal/xfce4-terminal/everslate.theme) into `~/.config/xfce4/terminal/colorschemes/`, then pick Everslate under Preferences → Appearance → Color scheme.

**Windows Terminal**: open Settings → Open JSON file (Ctrl+Shift+,), paste [`terminal/windows-terminal/Everslate.json`](./terminal/windows-terminal/Everslate.json) into the `schemes` array, then set `"colorScheme": "Everslate"` in a profile (or pick it in the color scheme dropdown).


## Editor & UI palette

### Backgrounds & UI

<table align="center">
<tr>
    <th>Preview</th>
    <th>Role</th>
    <th>Hex</th>
    <th>RGB</th>
</tr>
<tr>
    <td><img src="./assets/bg-base.svg?v=1.11.1" width="96" alt="bg-base swatch"></td>
    <td><code>Background</code></td>
    <td><code>#142024</code></td>
    <td><code>rgb(20, 32, 36)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-deep.svg?v=1.11.1" width="96" alt="bg-deep swatch"></td>
    <td><code>Deep background</code></td>
    <td><code>#0B171B</code></td>
    <td><code>rgb(11, 23, 27)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-panel.svg?v=1.11.1" width="96" alt="bg-panel swatch"></td>
    <td><code>Panel</code></td>
    <td><code>#0F1B1F</code></td>
    <td><code>rgb(15, 27, 31)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-elevated.svg?v=1.11.1" width="96" alt="bg-elevated swatch"></td>
    <td><code>Elevated background</code></td>
    <td><code>#1B2A2F</code></td>
    <td><code>rgb(27, 42, 47)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-active.svg?v=1.11.1" width="96" alt="bg-active swatch"></td>
    <td><code>Active</code></td>
    <td><code>#223136</code></td>
    <td><code>rgb(34, 49, 54)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-selection.svg?v=1.11.1" width="96" alt="bg-selection swatch"></td>
    <td><code>Selection</code></td>
    <td><code>#2C5561</code></td>
    <td><code>rgb(44, 85, 97)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-selection-strong.svg?v=1.11.1" width="96" alt="bg-selection-strong swatch"></td>
    <td><code>Selection (strong)</code></td>
    <td><code>#336C7D</code></td>
    <td><code>rgb(51, 108, 125)</code></td>
</tr>
<tr>
    <td><img src="./assets/border.svg?v=1.11.1" width="96" alt="border swatch"></td>
    <td><code>Border</code></td>
    <td><code>#3A464A</code></td>
    <td><code>rgb(58, 70, 74)</code></td>
</tr>
<tr>
    <td><img src="./assets/border-strong.svg?v=1.11.1" width="96" alt="border-strong swatch"></td>
    <td><code>Border (strong)</code></td>
    <td><code>#516065</code></td>
    <td><code>rgb(81, 96, 101)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-deep-slate.svg?v=1.11.1" width="96" alt="bg-deep-slate swatch"></td>
    <td><code>Deep slate (fill)</code></td>
    <td><code>#2A3B41</code></td>
    <td><code>rgb(42, 59, 65)</code></td>
</tr>
</table>


### Text

<table align="center">
<tr>
    <th>Preview</th>
    <th>Role</th>
    <th>Hex</th>
    <th>RGB</th>
</tr>
<tr>
    <td><img src="./assets/fg-plain.svg?v=1.11.1" width="96" alt="fg-plain swatch"></td>
    <td><code>Foreground</code></td>
    <td><code>#EDE6D5</code></td>
    <td><code>rgb(237, 230, 213)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-muted.svg?v=1.11.1" width="96" alt="fg-muted swatch"></td>
    <td><code>Muted</code></td>
    <td><code>#9CB1B8</code></td>
    <td><code>rgb(156, 177, 184)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-comment.svg?v=1.11.1" width="96" alt="fg-comment swatch"></td>
    <td><code>Comment</code></td>
    <td><code>#91A2A8</code></td>
    <td><code>rgb(145, 162, 168)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-faint.svg?v=1.11.1" width="96" alt="fg-faint swatch"></td>
    <td><code>Faint</code></td>
    <td><code>#91A2A8</code></td>
    <td><code>rgb(145, 162, 168)</code></td>
</tr>
<tr>
    <td><img src="./assets/term-bold.svg?v=1.11.1" width="96" alt="term-bold swatch"></td>
    <td><code>Terminal bold</code></td>
    <td><code>#DBBC7F</code></td>
    <td><code>rgb(219, 188, 127)</code></td>
</tr>
</table>


### Accents

<table align="center">
<tr>
    <th>Preview</th>
    <th>Role</th>
    <th>Hex</th>
    <th>RGB</th>
</tr>
<tr>
    <td><img src="./assets/primary.svg?v=1.11.1" width="96" alt="primary swatch"></td>
    <td><code>Primary (slate)</code></td>
    <td><code>#6997A7</code></td>
    <td><code>rgb(105, 151, 167)</code></td>
</tr>
<tr>
    <td><img src="./assets/keyword.svg?v=1.11.1" width="96" alt="keyword swatch"></td>
    <td><code>Keyword</code></td>
    <td><code>#6E9E8B</code></td>
    <td><code>rgb(110, 158, 139)</code></td>
</tr>
<tr>
    <td><img src="./assets/string.svg?v=1.11.1" width="96" alt="string swatch"></td>
    <td><code>String</code></td>
    <td><code>#8BBE95</code></td>
    <td><code>rgb(139, 190, 149)</code></td>
</tr>
<tr>
    <td><img src="./assets/function.svg?v=1.11.1" width="96" alt="function swatch"></td>
    <td><code>Function</code></td>
    <td><code>#6997A7</code></td>
    <td><code>rgb(105, 151, 167)</code></td>
</tr>
<tr>
    <td><img src="./assets/number.svg?v=1.11.1" width="96" alt="number swatch"></td>
    <td><code>Number</code></td>
    <td><code>#4196C7</code></td>
    <td><code>rgb(65, 150, 199)</code></td>
</tr>
<tr>
    <td><img src="./assets/operator.svg?v=1.11.1" width="96" alt="operator swatch"></td>
    <td><code>Operator</code></td>
    <td><code>#B7875A</code></td>
    <td><code>rgb(183, 135, 90)</code></td>
</tr>
<tr>
    <td><img src="./assets/special.svg?v=1.11.1" width="96" alt="special swatch"></td>
    <td><code>Special (gold)</code></td>
    <td><code>#DBBC7F</code></td>
    <td><code>rgb(219, 188, 127)</code></td>
</tr>
<tr>
    <td><img src="./assets/error-red.svg?v=1.11.1" width="96" alt="error-red swatch"></td>
    <td><code>Red (error & meter)</code></td>
    <td><code>#CF7677</code></td>
    <td><code>rgb(207, 118, 119)</code></td>
</tr>
</table>

