# Tipi Component - button

The Tipi `button` component is the basic styling for all buttons.
With the basic class **.button** we can display our desired tag as a button.

## Markup

```html
	<a href="{{href}}" class="">Add some whipped cream</a>

## Sass Helper Mixins

### construct_button-sizes();
Within this component we can easily set multiple heights on our buttons with the following mixin:

```sass
	$ @include construct_button-sizes($selector, $height, $gutter);

Arguments:

1. $selector: Define your element
2. $height: The actual height our $selector will be, based on the
3. $gutter: The horizontal spacing (as padding) around our button;