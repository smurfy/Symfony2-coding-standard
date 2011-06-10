Symfony2 PHP CodeSniffer Coding Standard
========================================

Based on openskys symfony2 codingstyle

Based on modifications from krymen (Scope checks)

Based on modifications from trylik (comment checks)

Installation
------------

1. Install phpcs:

       pear install PHP_CodeSniffer

2. Find your PEAR directory:

       pear config-show | grep php_dir

3. Copy, symlink or check out this repo to a folder called Symfony2 inside the
   phpcs `Standards` directory:

       cd /path/to/pear/PHP/CodeSniffer/Standards
       git clone git://github.com/smurfy/Symfony2-coding-standard.git Symfony2

4. Set Symfony2 as your default coding standard:

       phpcs --config-set default_standard Symfony2

5. ...

6. Profit!

       cd /path/to/my/project
       phpcs
       phpcs path/to/my/file.php
