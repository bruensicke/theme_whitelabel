# whitelabel webfront

This theme is the default skin for various web applications running CakePHP.
It can be easily customized to a certain Corporate Identity. It goals include:

**Assume nothing:** The Whitelabel theme should work without any additional content available.

**Keep it flexible:** The Whitelabel theme should be flexible in a way that changing some colors, some margins or settings it is possible to achieve a complete different look & feel. It can be a starting point for different branded themes.

**Keep it lightweight:** The Underlying markup is lightweight, easy to transform and free of markup-overhead just to produce more visually appealing results. The markup should treat the content with respect and work without the inclusion of tons of libraries.

## requirements

You need CakePHP 1.3 or higher, to make use of the webroot-folder within the themes-folder.

Also, you need to activate themes, by setting these variables in your AppController:

	public $view = 'Theme'; //tells CakePHP to use Themed View
	public $theme = ' <theme_name> '; //tells CakePHP to use this <theme_name>

### Wait, what about CakePHP 1.2?

If you need to use CakePHP 1.2 for whatever reason, try to symlink the webroot folder to `APP\webroot\themes\ <theme_name> `

## installation

Within your CakePHP applications root type the following command to add theme_whitelabel as a submodule.

	git submodule add https://github.com/bruensicke/theme_whitelabel.git app/views/themed/front

## License

Whitelabel Theme is licensed under the MIT license. The repository is secured because of the corporate styled branches.

## Sponsors

The initial development of Whitelabel Theme was done for an internal point-of-sale software for a german telecommunication company.

Whitelabel theme is developed by [brünsicke.com GmbH](http://bruensicke.com/). Get in touch if you need help making your next project.