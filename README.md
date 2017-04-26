# Onedrop.ImageSrcset

This adds responsive image sizes via the the srcset attribute to the default ``Neos.NodeTypes:Image`` and ``Neos.NodeTypes:TextWithImage`` NodeTypes.

## How-To:

### Install: 

Use the command ``composer require onedrop/imagesrcset`` to add this package as a requirement to your Neos project.  
(Or: Download the zip and unpack it to ``Packages/Application/Onedrop.ImageSrcset``)

### Configuration:

The following default values are provided by the plugin:

    Onedrop:
      ImageSrcset:
        sizes:          # dynamic array of sizes generated for the srcset attribute
          full: 2560
          large: 1280
          medium: 768
          small: 420
          tiny: 240

Feel free to add or remove sizes according to your specific needs.
