# Overview

This package is to help creating Json API Response. It follows the JSend standards (if you are not familiar with jsend, please refer to http://labs.omniti.com/labs/jsend)

# Installation
Add this code to composer.json:
```
	"thunderid/jsend": "dev-master"
```

and run
```
	composer update
```

# Usage
```php
	$jsend = new \ThunderID\jsend\jsend($status = "success|error|fail", $array);
	echo $jsend->toJson();
```
