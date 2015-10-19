Стандарт кодирования Miralogic
==============================

Установка
---------

#####Установить PHP_CodeSniffer:

    composer global require squizlabs/php_codesniffer 

#####Склонировать репозиторий:

    git clone https://github.com/itmh/php-standard-miralogic.git $HOME/.php-standard-miralogic

#####Создать в папке со стандартами симлинк на склонированный репозиторий

    ln -sv $HOME/.php-standard-miralogic/Miralogic $HOME/.composer/vendor/squizlabs/php_codesniffer/CodeSniffer/Standards

Использование
-------------

    phpcs --standard=Miralogic /path/to/file.php
    phpcs --standard=Miralogic /path/to/directory
