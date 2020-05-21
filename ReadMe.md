## iran-cities-json

This module exports two arrays:
- shahr
- ostan

shahrs and ostans are related by id

### Usage

```bash
yarn add iran-cities-json
#or
npm i iran-cities-json
```

```js
const { shahr, ostan } = require('iran-cities-json');
```

### My small note on usage

you can use the ids provided here on ui and backend validation and only store ids in db and don't worry about relations after that.

### Credits

All of the credits goes to work of [ahmadazizi](https://github.com/ahmadazizi/iran-cities)

Make sure to thank him ;)

### changelog

#### 1.0.0
released based on v2.0 release of ahmadazizi's work