# Geomatic.ly PHP Class

A php class to load your geomatic content. Visit geomatic.ly/docs/php for documentation.

## Usage

Set the config vars

    public $apikey = 'YOUR PROJECT KEY';//api key for your project

Load the class.

    require('geomaticly.php');

Load all the content blocks for this module.
    
    $block = $geomaticly->module("YOUR MODULE KEY");

Try it out.

    echo $block["SOME BLOCK METHOD"];


## Contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
