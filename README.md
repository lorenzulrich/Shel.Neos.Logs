# Logfile and exception viewer for Neos CMS   

[![Latest Stable Version](https://poser.pugx.org/shel/neos-logs/v/stable)](https://packagist.org/packages/shel/neos-logs)
[![Total Downloads](https://poser.pugx.org/shel/neos-logs/downloads)](https://packagist.org/packages/shel/neos-logs)
[![License](https://poser.pugx.org/shel/neos-logs/license)](https://packagist.org/packages/shel/neos-logs)

This package provides a new module in the backend for [NeosCMS](https://www.neos.io) to view logs
and exceptions of a Neos instance.

Usually it's recommended to use other more powerful tools for this use-case like [Sentry](http://sentry.io) 
or [Kibana](https://www.elastic.co/de/products/kibana), but there are cases in which those tools cannot be used.

This package was built to help in situations where one has to quickly look for something f.e. to 
understand an error the client had with their site.

## Installation

Run this in your site package:

    composer require --no-update shel/neos-logs
    
Then run `composer update` in your project root.

## Usage

After installation you will have a new backendmodule in Neos for administrators that will allow you to
view all local log and exception files.

Currently there is some basic highlighting and parsing done for the file to make it easier to see the details.
This will be improved in the future. Contributions are very welcome for this.

## Contributions

Contributions are very welcome! 

Please create detailed issues and PRs.  

**If you use this package and want to support or speed up it's development, [get in touch with me](mailto:hyphens@helzle.it).**

Or you can also support me directly via [patreon](https://www.patreon.com/shelzle).

## License

See [License](./LICENSE.txt)
