# ci3-strapped
Codeigniter 3 with bootstrap

This package is add-ons to be used on top of standard CodeIgniter package to enable Twitter bootstrap functionalities to be used.

## What's included?

* [CodeIgniter](https://github.com/bcit-ci/CodeIgniter)
* [Twitter Bootstrap](https://github.com/twbs/bootstrap)
* [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

## Use
* Download the latest Codeigniter package [CodeIgniter 3.0](https://github.com/bcit-ci/CodeIgniter/)
* Download the latest [ci3-strapped package](https://github.com/imehedi/ci3-strapped/)

## Docs

### Clean Installation

* Perform a clean install of Codeigniter 3.0.
* Copy ci3-strapped/assets to your webroot. 
  For example, if your website base is http://example.com/ then you need to make http://example.com/assets/
  If your CodeIgniter installation is in subdirectory, then check your application/config.php for "$config['base_url']". Copy ci3-strapped/assets needs to be in the same path as $config['base_url'].

* Copy ci3-strapped/application   -> CodeIgniter_installation/application

### Applying to an existing Installation

ci3-strapped requires URL helper to be autoloaded.

* Open the application/config/autoload.php in your existing CodeIgniter 3.0 installation. Find for $autoload['helper']. You will need to ensure the array contains url in it.

For example: $autoload['helper'] = array('url', 'other_helper');

* This package makes ammendments to the Welcome controller by adding header, navigation and footer views. Also, the welcome_message view is altered.
 You will need to take care of any adjustments here.

## License

This package is available as-is and does not guarantee continuous upgrading to subsequent bootstrap versions.
License information for bootstrap is available from https://github.com/twbs/bootstrap 
License information on Font-Awesome library is available from http://fontawesome.io/license
License information on CodeIgniter is available from https://github.com/bcit-ci/CodeIgniter/blob/develop/user_guide_src/source/license.rst
