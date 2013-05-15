PHP CodeSniffer pre-commit hook for CakePHP
=========================

This repo provide the pre-commit hook files for windows or unix system.

# Installation

Obviously, you need [PHP CodeSniffer](http://pear.php.net/package/PHP_CodeSniffer/download) for this repository to have any meaning.

Its generally recommended to install these code sniffs with the PEAR
installer:

	pear channel-discover pear.cakephp.org
	pear install cakephp/CakePHP_CodeSniffer

Install the needed pre-commit file for your operating systmem to .git/hooks/pre-commit
