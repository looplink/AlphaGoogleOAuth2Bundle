
## Install

add

    // app/AppKernel.php
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new Alpha\GoogleOAuth2Bundle\AlphaGoogleOAuth2Bundle(),
        );
        // ...
    
        return $bundles;
    }

add

    // app/autoload.php
    $loader->registerNamespaces(array(
        // ...
        'Alpha'            => __DIR__.'/../vendor/bundles',
    ));


