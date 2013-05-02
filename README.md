#Yaml Component

Yaml implements most of the YAML 1.2 specification.

    use Symfony\Component\Yaml\Yaml;

    $array = Yaml::parse($file);

    print Yaml::dump($array);

##Installation

You can install Yaml through [Composer](http://getcomposer.org):

    {
        "require": {
            "mauris/yaml": "1.0.*"
        }
    }

Then run:

    $ composer install

##Resources

You can run the unit tests with the following command:

    $ cd path/to/Symfony/Component/Yaml/
    $ composer.phar install --dev
    $ phpunit
