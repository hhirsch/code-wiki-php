# PHP Interpreter
The source code for the PHP interpreter can be found on [github](https://github.com/php/php-src/).

You'll find the following directories:

## Zend
The core of the PHP language. It handles parsing, execution, and compilation of PHP code.

## TSRM
Stands for Thread Safe Resource Manager. It contains code related to thread safety and resource management in the PHP interpreter.

## ext
PHP's standard extension modules like gd or mysql.

## sapi
Server API modules. Each subdirectory represents a particular server interface. For example for apache or the command line.

## main
This directory contains the main PHP interpreter loop, which handles the initialization, configuration, and execution of PHP scripts.

## TSRM
Similar to the TSRM directory mentioned earlier, this directory contains code related to thread safety and resource management but with non-thread-safe builds.

## ZendEngine3 
Zend Engine 3, the core of PHP 7 and later versions. 

## win32
Windows specific code and files
