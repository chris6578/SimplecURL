# SimplecURL

[![Build Status](https://travis-ci.org/SimplecURL/SimplecURL.svg?branch=master)](https://travis-ci.org/SimplecURL/SimplecURL)
[![Code Climate maintainability](https://img.shields.io/codeclimate/maintainability-percentage/SimplecURL/SimplecURL)](https://codeclimate.com/github/SimplecURL/SimplecURL)

SimplecURL is a simple and modern wrapper around PHP's [`ext-curl`](https://www.php.net/manual/en/book.curl.php).

```php
$client = new SimplecURL\Client;
$res = $client->request('GET', 'http://127.0.0.1:8080/');

echo $res->getBody();
```

## Installation

```sh
composer require simplecurl/simplecurl
```

## Docs

Docs can be found in `/docs` or at [https://simplecurl.github.io/SimplecURL/](https://simplecurl.github.io/SimplecURL/).
