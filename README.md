Pico Social Share
==========
The plugin will add social share links to your [Pico] (!https://github.com/gilbitron/Pico) posts and pages. Supported services: Twitter, Facebook, Google+, LinkedIn.

## Installation
1. Copy `pico_share.php` to the `plugins` folder.
2. Update your theme to use the links generated by the plugin.
3. Set configuration variables if defaults are not suitable.

## Configuration
**services** - select which services are enabled. _**default**_: all services enabled  
`$config['social']['services'] = array('twitter' => true, 'facebook' => true, 'google' => true, 'linkedin' => false);`
**output** - select how services will be displayed. _**default**_: list. _**options**_: list | link  
`$config['social']['output'] = 'link';`  
**class_prefix** - add class(es) to `a` tags. by default, every service will have a `btn-service` class. _**default**_: btn-  
`$config['social']['class_prefix'] = 'buttons btn-';`  

## Setting up the theme
Just add `{{ social_share }}` to your theme.

## NOTE
There is no stylesheet provided. If you need help with styles, check [pure-extras] (!https://github.com/narcis-radu/pure-extras), [social-sharing] (!https://github.com/cferdinandi/social-sharing/) or any CSS snippets.
