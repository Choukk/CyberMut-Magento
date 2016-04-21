# CyberMut for Magento

This extension provides CM-CIC p@iement (CyberMUT / CIC payment) integration.
For payments through Credit Mutuel Group (Credit Mutuel, CIC, OBC).
Compatible with CM-CIC versions 1.2 and 3.0.

## Merchant Back Office Configuration

In your merchant back office configuration, you have to configure the 2 urls below to keep the module working (merchant payment authorisation).

One time order :
* [url_website]/cybermut/payment/notify/

Multiple time order :
* [url_website]/cybermut/several/notify/


## Disclamer

Per to the OSL 3 License, the Original Work is provided under this License on an "AS IS" BASIS and WITHOUT WARRANTY, either express or implied, including, without limitation, the warranties of non-infringement, merchantability or fitness for a particular purpose. THE ENTIRE RISK AS TO THE QUALITY OF THE ORIGINAL WORK IS WITH YOU. This DISCLAIMER OF WARRANTY constitutes an essential part of this License. No license to the Original Work is granted by this License except under this disclaimer.

## Contributing

This module is an **open-source extension** to the Magento e-commerce solution. Everyone is welcome and even encouraged to contribute with their own improvements.

### Requirements for contributing

Contributors **must** follow the following rules:

* **Make your Pull Request on the "master" branch**
* Do NOT update the module's version number.
* Follow [the coding standards][1].

### Contributing process in details

Contributors wishing to edit a module's files should follow the following process:

1. Create your GitHub account, if you do not have one already.
2. Fork the ganalytics project to your GitHub account.
3. Clone your fork to your local machine in the ```/modules``` directory of your Magento installation.
4. Create a branch in your local clone of the module for your changes.
5. Change the files in your branch. Be sure to follow [the coding standards][1]!
6. Push your changed branch to your fork in your GitHub account.
7. Create a pull request for your changes **on the _'dev'_ branch** of the module's project. If you need help to make a pull request, read the [Github help page about creating pull requests][2].
8. Wait for one of the core developers either to include your change in the codebase, or to comment on possible improvements you should make to your code.

That's it: you have contributed to this open-source project! Congratulations!

[1]: http://devdocs.magento.com/guides/v2.0/coding-standards/code-standard-php.html
[2]: https://help.github.com/articles/using-pull-requests
