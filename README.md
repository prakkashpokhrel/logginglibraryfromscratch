# logginglibraryfromscratch
Simple logging library

This logging library contains following features. 
 
A simple interface to define the essential behavior of a log
At least one concrete instance that persists the logs to the filesystem, and which is suitable for production.
Support for segmenting logs by level (e.g. Debug, Information, Warning, etc.)
Any other supporting code that makes to make it easier to work with implementations of your interface, helps to separate concerns, makes the logging library more composable, etc.
A suite of tests that assert the correct behavior of the library
