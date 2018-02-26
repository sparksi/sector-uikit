# Sector Responsive Layout

### Naming convention for grid modifiers. For example:

* `.responsive-layout--t2` translates to layout of 2 columns for tablet large and up breakpoint ('t' for tablet-large)
* `.responsive-layout--d3` translates to layout of 3 columns for desktop and up ('d' for desktop).
* `.responsive-layout--w4` translates to layout of 3 columns for wide and up ('w' for wide).

Intention is to use any combination of these modifiers to achieve desired grid configuration.

For example:

```
<div class="responsive-layout responsive-layout--t2 responsive-layout--w4">
    <div class="responsive-layout__item"> ... </div>
    <div class="responsive-layout__item"> ... </div>
    <div class="responsive-layout__item"> ... </div>
    <div class="responsive-layout__item"> ... </div>
</div>
```

* By default, without any modifiers, the .responsive-layout component will squash all child
* `.responsive-layout__item` elements into the same row, without any wrapping.