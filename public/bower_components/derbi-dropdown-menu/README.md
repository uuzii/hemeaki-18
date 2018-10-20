[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/TherapyChat/derbi-dropdown-menu)
[![Build status](https://travis-ci.org/TherapyChat/derbi-dropdown-menu.svg?branch=master)](https://travis-ci.org/TherapyChat/derbi-dropdown-menu)

## &lt;derbi-dropdown-menu&gt;

Material design: [Dropdown menus](https://material.io/guidelines/components/buttons.html#buttons-dropdown-buttons)

`derbi-dropdown-menu` is similar to a native browser select element.
`derbi-dropdown-menu` works with selectable content.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../neon-animation/web-animations.html">
    <link rel="import" href="derbi-dropdown-menu.html">
    <link rel="import" href="../paper-item/paper-item.html">
    <link rel="import" href="../paper-listbox/paper-listbox.html">
    <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
    <style is="custom-style" include="demo-pages-shared-styles">
      derbi-dropdown-menu, paper-listbox {
        width: 250px;
      }
      derbi-dropdown-menu {
        height: 200px;
        margin: auto;
        display: block;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<derbi-dropdown-menu label="Dinosaurs">
  <paper-listbox slot="dropdown-content" selected="1">
    <paper-item>allosaurus</paper-item>
    <paper-item>brontosaurus</paper-item>
    <paper-item>carcharodontosaurus</paper-item>
    <paper-item>diplodocus</paper-item>
  </paper-listbox>
</derbi-dropdown-menu>
```

### Changes in 2.0
- `paper-menu-button 2.0` depends on `neon-animation 2.0`, which doesn't import the Web Animations polyfill, so you'll have to import it ([see example](demo/index.html))