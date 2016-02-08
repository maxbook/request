# PHPRequest - Lightweight PHP HTTP client

## Super simple to use
Request is designed to be the simplest way possible to make http calls in PHP.
```php
require 'Request.php';
$request = new Request();
$res = $request->get('http://www.google.com');

echo $res['body']; // Show the HTML for the Google homepage.
```

## Table of contents

- [Request defaults](#streaming)
- [Request response](#streaming)
- [Post](#forms)
- [Get](#http-authentication)
- [Patch](#http-authentication)
- [Delete](#http-authentication)
- [Custom request](#http-authentication)
- [Response type](#response-type)
- [Custom HTTP Headers](#custom-http-headers)

---
