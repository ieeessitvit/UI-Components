# Toggle switch

This is a toggle swich made in vanilla CSS.

All the switch styles can be found in `switch-styles.css` in the `css` folder.

The HTML code for the switch is as follows:

```html
<label class="switch" aria-label="toggle switch">
	<input type="checkbox" class="toggle-switch" />
	<span class="slider"></span>
</label>
```

these are the properties of the switch can be customised using the following CSS custom properties:

```css
.switch {
	/* switch properties declaration */
	--clr-bg-off: #bfbebe;
	--clr-bg-on: #00dc46;
	--dot-clr: #fff;
	--width: 100px;
	--height: 50px;
	--animation-length: 200ms;
}
```
