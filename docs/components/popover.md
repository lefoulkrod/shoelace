# Tooltip

[component-header:sl-popover]

```html preview
<sl-popover trigger="click">
  <sl-button>Hover Me</sl-button>
  <div slot="rich-content">
    <sl-menu
  style="max-width: 200px; border: solid 1px var(--sl-panel-border-color); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-item value="1">Option 1</sl-menu-item>
  <sl-menu-item value="2">Option 2</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item value="3">Option 3</sl-menu-item>
  <sl-menu-item value="4">Option 4</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item value="5">Option 5</sl-menu-item>
  <sl-menu-item value="6">Option 6</sl-menu-item>
</sl-menu>
  </div>
</sl-popover
```