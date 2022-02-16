# Custom valet driver for WordPress/phpMyAdmin/custom PHP installations using laravel valet

Run any php app with laravel valet using steps described as below:

1. Create project directory & run valet park if not you've not parked already

#### this step is optional if valet is parked at another directory

`mkdir projects/wordpress`
#### download and extract wordpress/your custom project files in this directory

`cd projects && valet park`

2. Download the Custom valet driver into your Valet Drivers directory

`cd ~/.config/valet/Drivers && curl -O https://raw.githubusercontent.com/naresh335/custom-php-valet-driver/main/PhpValetDriver.php`

3. Restart valet

`valet restart`
