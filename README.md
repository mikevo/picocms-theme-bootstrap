# picocms-bootstrap-theme
This is a theme designed using [Bootstrap](https://github.com/twbs/bootstrap/) to work with [Pico CMS](https://github.com/picocms/Pico).

## Config
Ensure that the following is configured in <code>config/config.php</code>

    $config['base_url'] = 'https://sub.example.com/';
    $config['logo_name'] = 'logo.svg';
    $config['parent_site_name'] = 'Parent Site';
    $config['parent_site_url'] = 'https://example.com';
    $config['image_prefix'] = '/static/img';
    $config['bootstrap_cdn'] = '/static'; // e.g.: https://maxcdn.bootstrapcdn.com
    $config['jquery_cdn'] = '/static'; // e.g.: https://code.jquery.com
    $config['links'] = array(
      'https://wiki.example.com/' => 'Wiki',
    );


## License
The basic layout is taken from [Bootstrap Doc](https://github.com/twbs/bootstrap/doc) and therefore could be under under [CC BY 3.0](https://github.com/twbs/bootstrap/blob/master/docs/LICENSE) but they state in their [README](https://github.com/twbs/bootstrap#copyright-and-license) that code is under the MIT license and therefore all modifications are licensed under the MIT license.
