# Logger

A module that allows you to have logs of your application in a simple way.

## How to Use

Call the static method *"log"* of the [Logger](src/logger/Logger.php) class and then pass the message and log level respectively. The log levels are included in the Logger class as constants.

```php
<?php

use Logger\Logger;

/**
 * the first parameter is the log message
 * the second parameter is the log level
 */

Logger::log("Hello, I\'m a debug message", Logger::DEBUG);

```

***In log/application.log***

```txt
[DEBUG] 2023-02-12 2:10 AM Hello, I'm a debug message
```
