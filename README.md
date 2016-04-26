# Academy SVG Icon Sprite

The svg should always have the class `.icon` and be placed inside of a parent element. Height and width should be applied to the parent element, not the SVG itself.
```
<div class="btn">
	<svg class="icon">
		<use xlink:href="#icon-name" />
		//href should reference the ID of whatever icon you need to display
	</svg>
</div>
```

The `.icon` class makes the SVG a block level element and gives it a width and height of 100%.
```
.icon {
	display: block;
	height: 100%;
	width: 100%;
}
```

[See all the icons on Codepen](http://s.codepen.io/academyux/debug/1abff3ecd7101a9fde9e8db6828bce11)

Icons:
- amex
- caret-down
- caret-left
- caret-right
- caret-up
- cart
- chat
- check-circle
- check
- chevron-down
- chevron-left
- chevron-right
- chevron-up
- color-wheel
- crosshair
- discover
- facebook
- info-circle
- instagram
- invodo-360
- loading dots
- lock
- logo
- map-pin
- mastercard
- minus-circle
- minus
- paypal
- pinterest
- play-circle
- plus-circle
- plus
- refresh
- search
- times-circle
- times
- twitter
- visa
- youtube
- zoom-in
- zoom-out
