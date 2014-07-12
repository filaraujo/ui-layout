ui-layout
==

A responsive ui element that creates an app-like structure containing a drawer.


### Upcoming features
* cleaning up css
* support both left and right nav - and both at same time
* stretch support for tv

##Markup
``` html
<ui-layout>
    <div drawer parallax right>
        ...
    </div>
    <div main>
        ...
    </div>
</ui-layout>
```

##Drawer Configuration
drawer element can be configured with the following options

``` html
<!-- slide effect -->
<div drawer slide></div>

<!-- parallax effect -->
<div drawer parallax></div>

<!-- parallax effect -->
<div drawer pan></div>

<!-- positions drawer on right -->
<div drawer right></div>

<!-- positions drawer on right with a parallax effect -->
<div drawer right parallax></div>
```
