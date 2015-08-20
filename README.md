# WordPress
Standard Configuration Files for WordPress

## How to use?
We are using WP Packagist to maintain the plugins necessary for the wordpress install. (http://wpackagist.org/)

Each folder represents a generic use case. To run them, you must have composer installed (https://getcomposer.org/) 

1. Add the repository to your composer.json
2. Add the desired plugins and themes to your requirements using wpackagist-plugin or wpackagist-theme as the vendor name.
3. Run $ composer.phar update
4. Packages are installed to wp-content/plugins/ or wp-content/themes/