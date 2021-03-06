# Theme Whitelabel

This is a theme used for various web applications running CakePHP 1.3.
It can be easily customized to a certain Corporate Identity. It goals include:

**Assume nothing:** The Whitelabel theme should work without any additional content available.

**Keep it flexible:** The Whitelabel theme should be flexible in a way that by changing some colors, some margins or settings it is possible to achieve a complete different look & feel. It can be a starting point for different branded themes.

**Keep it lightweight:** The Underlying markup is lightweight, easy to transform and free of markup-overhead just to produce more visually appealing results. The markup should treat the content with respect and work without the inclusion of tons of libraries.

## Requirements

You need CakePHP 1.3 or higher, to make use of the webroot-folder within the themes-folder.

Also, you need to activate themes, by setting these variables in your AppController:

	public $view = 'Theme'; //tells CakePHP to use Themed View
	public $theme = ' <theme_name> '; //tells CakePHP to use this <theme_name>

### Wait, what about CakePHP 1.2?

If you need to use CakePHP 1.2 for whatever reason, try to symlink the webroot folder to `APP\webroot\themes\ <theme_name> `

## Installation

Within your CakePHP applications root type the following command to add theme_whitelabel as a git submodule.

	git submodule add git@github.com:bruensicke/theme_whitelabel.git app/views/themed/front

## Development

Whitelabel Theme can easily be developed without CakePHP running or PHP parsing at all. Just open `webroot/index.html` in your favourite browser.
All Assets (js, css, img) should be loaded as usual and you can change markup to your likings and see how they render. Please notice, that changes to the markup will not reflect the themes layouts within CakePHP. It is more a preview of how assets will be rendered.
Therefore, to change something crucial, you have to work within the folders `/css`, `/js` or `/img`. Make sure to reference every other asserts relative, so both access methods remain intact.

## License

Whitelabel Theme is licensed under the MIT license.
The repository is secured because of the corporate styled branches.

## Sponsors

The initial development of Whitelabel Theme was done for an internal point-of-sale software for a german telecommunication company.

Whitelabel theme is developed by [brünsicke.com GmbH](http://bruensicke.com/). Get in touch if you need help making your next project.