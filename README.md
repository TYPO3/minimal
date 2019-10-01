# Minimal TYPO3 packages

This package provides composer requirements to the minimal set of code
(in terms of TYPO3 system extensions) that is required to run TYPO3.

## Installation

`composer require typo3/minimal`

This will install all code that is required and will set up the document root
with the required entry scripts.

Additional TYPO3 core extensions can subsequently be added with composer.

E.g.: `composer require typo3/cms-felogin`
