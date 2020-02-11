# Really Funny Jokes


[![Build Status](https://travis-ci.com/bagwaa/really-funny-jokes.svg?branch=master)](https://travis-ci.com/bagwaa/really-funny-jokes)
[![StyleCI](https://github.styleci.io/repos/239808252/shield?branch=master)](https://github.styleci.io/repos/239808252)

Don't let your PHP apps be sad and gloomy, insert this joke package and never be without a good joke again!

## Installation

Use the package manager [composer](https://getcomposer.org/) to install really-funny-jokes.

```php
composer require bagwaa/really-funny-jokes
````

## Usage


```php
<?php

use Bagwaa\ReallyFunnyJokes\JokeFactory;

$jokes = new JokeFactory();
$joke = $jokes->getRandomJoke();
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
