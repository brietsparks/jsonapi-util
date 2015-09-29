# jsonapi-util
Util functions for working with jsonapi 1.0 structures

## Install
You can install using Node Package Manager (`npm`):

```
npm install jsonapi-util
```

## Usage
```
var jsonapi-util = require('jsonapi-util')
```

## API
### Methods
#### parse(obj)
Parse a jsonapi document object to resolves includes and returns a tree structured object.

#### isDocument(obj)
Verify if a object is a valid JSON API document

#### isResoucre(obj)
Verify if a object is a valid JSON API resource object

