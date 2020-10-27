Magento 2 Bones
===================

### Description

A starter project for beginning module development in Magento 2. Also a template for future Magento 2 projects.

Setting up the default files required by Magento 2 when building a custom module decreases development time
and maintains consistency across projects.

Facts
-----

 * Version: 1.2.1
 * [Repository on Github](https://github.com/iods/magento2-bones)


Getting Started
---------------
Instructions on how to download, install, and configure the module. 

### Requirements

 * [Git](http://git-scm.com)
 * [Composer](http://getcomposer.org)
 
### Known Issues

 * Link to any Github issues, or list issues w/ Magento 2 compatibility or Extension compatibility

### Installation

Includes a series of step-by-step examples for installation and configuration.
```
$ composer require iods/module-bones
$ bin/magento module:enable Iods_Bones
$ bin/magento setup:upgrade
$ bin/magento cache:flush 
```

Development
-----------

### Structure

How does it work? What components in the module exist. What is different. Link to devdocs.

Finishing w/ an example of system information of demo of the module for your team.


### Extensibility

Includes a series of step-by-step examples for extending the module and code snippets of the extension points.

#### Events

A list of events dispatched by the module.

#### Layouts

Does it introduce layouts or layout handles?


### UI Components

Does the module introduce any UI components or the configuration files, where are they?


### Public API

Does the module introduce any public API? what services are introduced?

```bash
\Magento\Sales\Api\InvoiceOrderInterface
  * Create an Invoice
  * Change status and state
```


### Tests

Includes a series of step-by-step examples for testing the module.


### Code Styles

Includes any relevant code style information or documentation.


### Configuration

Overview of the admin/configuration settings within the module.

| group | field | description |
|-------|-------|-------------|
|web    |default|example      |
|web    |default|example      |
|admin  |default|example      |


Support
-------

If you have any issues with this project, open an issue on [Github](https://github.com/iods/magento2-bones/issues)


Developer
---------

**Rye Miller**

 * [GitHub](http://github.com/iods/)
 * [@ryemiller](https://twitter.com/ryemiller)
 * [Portfolio](https://ryemiller.io)
 * [Developer Rants](http://drkstr.dev)


Versioning	
----------

For transparency into the release cycle and in striving to maintain backward compatibility, this project is
maintained under [the Semantic Versioning guidelines](http://semver.org/).


License
-------

This project/code is released under [the MIT license](https://github.com/iods/magento2-bones/LICENSE).


Copyright
---------

(c) 2020 Rye Miller. All Rights Reserved.
