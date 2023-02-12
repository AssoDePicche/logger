# Logger

A module that allows you to have logs of your application in a simple way.

## How to Use

Call the static method *"log"* of the [Logger](src/logger/Logger.php) class and then pass the message and log level respectively. The log levels are included in the Logger class as constants.

```php
<?php

use Logger\Logger;

/**
 * @param string $message
 * @param string $level
 */

Logger::log("Hello, I\'m a debug message", Logger::DEBUG);

/**
 * In log/application.log file
 * 
 * [DEBUG] 2023-02-12 2:10 AM Hello, I'm a debug message
 */

```

## How to Install

You can clone the repository on your desktop or simply download the compressed file by clicking on Code and then Download ZIP.

```bash
git clone git@github.com:AssoDePicche/logger.git
```
