

AppKernel.php
$bundles = array(
    new Alpha\GoogleOAuth2Bundle\AlphaGoogleOAuth2Bundle(),
);

autoload.php
$loader->registerNamespaces(array(
    'Alpha'            => __DIR__.'/../vendor/bundles',
));


