<div align="center">

# Everslate

</div>

## Terminal theme

The colors a terminal actually renders: the 16 ANSI slots plus background,
foreground, cursor and selection, packaged for import.

### Terminal ANSI 16

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
    <td align="center"><img src="./assets/ansi-0.svg" width="64" alt="ansi-0 swatch"><br><code>#666F64</code></td>
    <td align="center"><img src="./assets/ansi-1.svg" width="64" alt="ansi-1 swatch"><br><code>#4B9E74</code></td>
    <td align="center"><img src="./assets/ansi-2.svg" width="64" alt="ansi-2 swatch"><br><code>#819B69</code></td>
    <td align="center"><img src="./assets/ansi-3.svg" width="64" alt="ansi-3 swatch"><br><code>#E5B567</code></td>
    <td align="center"><img src="./assets/ansi-4.svg" width="64" alt="ansi-4 swatch"><br><code>#4196C7</code></td>
    <td align="center"><img src="./assets/ansi-5.svg" width="64" alt="ansi-5 swatch"><br><code>#B4A2D8</code></td>
    <td align="center"><img src="./assets/ansi-6.svg" width="64" alt="ansi-6 swatch"><br><code>#66A5AD</code></td>
    <td align="center"><img src="./assets/ansi-7.svg" width="64" alt="ansi-7 swatch"><br><code>#EDE6D5</code></td>
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
    <td align="center"><img src="./assets/ansi-8.svg" width="64" alt="ansi-8 swatch"><br><code>#7A8478</code></td>
    <td align="center"><img src="./assets/ansi-9.svg" width="64" alt="ansi-9 swatch"><br><code>#E67E80</code></td>
    <td align="center"><img src="./assets/ansi-10.svg" width="64" alt="ansi-10 swatch"><br><code>#A7C080</code></td>
    <td align="center"><img src="./assets/ansi-11.svg" width="64" alt="ansi-11 swatch"><br><code>#DBC07F</code></td>
    <td align="center"><img src="./assets/ansi-12.svg" width="64" alt="ansi-12 swatch"><br><code>#7FBBB3</code></td>
    <td align="center"><img src="./assets/ansi-13.svg" width="64" alt="ansi-13 swatch"><br><code>#D699B6</code></td>
    <td align="center"><img src="./assets/ansi-14.svg" width="64" alt="ansi-14 swatch"><br><code>#83C092</code></td>
    <td align="center"><img src="./assets/ansi-15.svg" width="64" alt="ansi-15 swatch"><br><code>#F2EFDF</code></td>
</table>

### Terminal example

<div align="center">
<img src="./assets/terminal-example.png" width="680" alt="Everslate terminal example">
</div>


### Install

**iTerm2** (and anything that imports `.itermcolors`): Settings → Profiles → Colors → Color Presets → Import… and pick [`everslate.itermcolors`](./everslate.itermcolors). Many other terminals and tools accept this format directly or through converters.


## Editor & UI palette

A broader role set built on the same base — background ladder, text roles
and accents for editors, UIs and other tooling. These are Everslate roles,
not ANSI slots, and are **not** part of the terminal theme pack above.

### Backgrounds & UI

<table align="center">
<tr>
    <th>Preview</th>
    <th>Role</th>
    <th>Hex</th>
    <th>RGB</th>
</tr>
<tr>
    <td><img src="./assets/bg-base.svg" width="96" alt="bg-base swatch"></td>
    <td><code>Background</code></td>
    <td><code>#1B1F22</code></td>
    <td><code>rgb(27, 31, 34)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-deep.svg" width="96" alt="bg-deep swatch"></td>
    <td><code>Deep background</code></td>
    <td><code>#111619</code></td>
    <td><code>rgb(17, 22, 25)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-panel.svg" width="96" alt="bg-panel swatch"></td>
    <td><code>Panel</code></td>
    <td><code>#16191D</code></td>
    <td><code>rgb(22, 25, 29)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-elevated.svg" width="96" alt="bg-elevated swatch"></td>
    <td><code>Elevated background</code></td>
    <td><code>#22292D</code></td>
    <td><code>rgb(34, 41, 45)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-active.svg" width="96" alt="bg-active swatch"></td>
    <td><code>Active</code></td>
    <td><code>#283035</code></td>
    <td><code>rgb(40, 48, 53)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-selection.svg" width="96" alt="bg-selection swatch"></td>
    <td><code>Selection</code></td>
    <td><code>#2C5561</code></td>
    <td><code>rgb(44, 85, 97)</code></td>
</tr>
<tr>
    <td><img src="./assets/bg-selection-strong.svg" width="96" alt="bg-selection-strong swatch"></td>
    <td><code>Selection (strong)</code></td>
    <td><code>#336C7D</code></td>
    <td><code>rgb(51, 108, 125)</code></td>
</tr>
<tr>
    <td><img src="./assets/border.svg" width="96" alt="border swatch"></td>
    <td><code>Border</code></td>
    <td><code>#3A4741</code></td>
    <td><code>rgb(58, 71, 65)</code></td>
</tr>
<tr>
    <td><img src="./assets/border-strong.svg" width="96" alt="border-strong swatch"></td>
    <td><code>Border (strong)</code></td>
    <td><code>#52615A</code></td>
    <td><code>rgb(82, 97, 90)</code></td>
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
    <td><img src="./assets/fg-plain.svg" width="96" alt="fg-plain swatch"></td>
    <td><code>Foreground</code></td>
    <td><code>#EDE6D5</code></td>
    <td><code>rgb(237, 230, 213)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-muted.svg" width="96" alt="fg-muted swatch"></td>
    <td><code>Muted</code></td>
    <td><code>#A6B0A0</code></td>
    <td><code>rgb(166, 176, 160)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-comment.svg" width="96" alt="fg-comment swatch"></td>
    <td><code>Comment</code></td>
    <td><code>#859289</code></td>
    <td><code>rgb(133, 146, 137)</code></td>
</tr>
<tr>
    <td><img src="./assets/fg-faint.svg" width="96" alt="fg-faint swatch"></td>
    <td><code>Faint</code></td>
    <td><code>#7A8478</code></td>
    <td><code>rgb(122, 132, 120)</code></td>
</tr>
<tr>
    <td><img src="./assets/term-bold.svg" width="96" alt="term-bold swatch"></td>
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
    <td><img src="./assets/primary.svg" width="96" alt="primary swatch"></td>
    <td><code>Primary (slate)</code></td>
    <td><code>#79A9B8</code></td>
    <td><code>rgb(121, 169, 184)</code></td>
</tr>
<tr>
    <td><img src="./assets/keyword.svg" width="96" alt="keyword swatch"></td>
    <td><code>Keyword</code></td>
    <td><code>#4B9E74</code></td>
    <td><code>rgb(75, 158, 116)</code></td>
</tr>
<tr>
    <td><img src="./assets/string.svg" width="96" alt="string swatch"></td>
    <td><code>String</code></td>
    <td><code>#819B69</code></td>
    <td><code>rgb(129, 155, 105)</code></td>
</tr>
<tr>
    <td><img src="./assets/function.svg" width="96" alt="function swatch"></td>
    <td><code>Function</code></td>
    <td><code>#66A5AD</code></td>
    <td><code>rgb(102, 165, 173)</code></td>
</tr>
<tr>
    <td><img src="./assets/number.svg" width="96" alt="number swatch"></td>
    <td><code>Number</code></td>
    <td><code>#4196C7</code></td>
    <td><code>rgb(65, 150, 199)</code></td>
</tr>
<tr>
    <td><img src="./assets/operator.svg" width="96" alt="operator swatch"></td>
    <td><code>Operator</code></td>
    <td><code>#B77E64</code></td>
    <td><code>rgb(183, 126, 100)</code></td>
</tr>
<tr>
    <td><img src="./assets/special.svg" width="96" alt="special swatch"></td>
    <td><code>Special (gold)</code></td>
    <td><code>#E5B567</code></td>
    <td><code>rgb(229, 181, 103)</code></td>
</tr>
<tr>
    <td><img src="./assets/error-red.svg" width="96" alt="error-red swatch"></td>
    <td><code>Error red</code></td>
    <td><code>#E67E80</code></td>
    <td><code>rgb(230, 126, 128)</code></td>
</tr>
<tr>
    <td><img src="./assets/alert-red.svg" width="96" alt="alert-red swatch"></td>
    <td><code>Alert red</code></td>
    <td><code>#F85552</code></td>
    <td><code>rgb(248, 85, 82)</code></td>
</tr>
<tr>
    <td><img src="./assets/meter-red.svg" width="96" alt="meter-red swatch"></td>
    <td><code>Meter red</code></td>
    <td><code>#C0686A</code></td>
    <td><code>rgb(192, 104, 106)</code></td>
</tr>
</table>

