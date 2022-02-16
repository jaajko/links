## Breaking down <a> attributes

1.) class="button button-default" | The first "button" here is telling this <a> tag that it should make this element a button and applies the default styling in `css/brands.css`.

The second portion, button-default, is declaring the specific brand style you would like to apply. Here we're applying the "default" style and color.

If you want to make this button to use the brand colors for Discord, just change "button-default" to "button-discord". Brands are found in `css/brands.css`. You can always edit & add your own there.

2.) Replace the # in href="#" with the desired target URL for the button.

3.) target="_blank" | This attribute opens links in a new tab. Remove this attribute to prevent links from opening in a new tab.

4.) rel="noopener" | This attribute instructs the browser to navigate to the target resource without granting the new browsing context access to the document that opened it.
This is especially useful when opening untrusted links. https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/noopener

## Breaking down the <img> attributes

1.) class="icon" | This class is telling the <img> tag that it should use the styling for icons found in `css/brands.css`.

2.) src="icons/[icon_name].svg" | This defines the icon you would like to display from the icons/ folder. For example, you can change this to src="icons/discord.svg" to use the Discord icon.
Add your own 24x24 icons to the "icons" folder to reference them. We recommend providing a SVG. 
