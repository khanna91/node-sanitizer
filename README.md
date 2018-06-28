# node-sanitizer
Node Object Sanitizer


## Installation

Clone the repo and make it yours:

```bash
yarn add node-sanitizer
```

## Use

```
const sanitizer = require('sanitizer');

const obj = {
  username: 'some@email.com',
  password: 'veryverysecret',
  fullname: 'Awesome guy',
};

const sanitizedObject = sanitizer(obj, ['password]);

console.log(sanitizedObject);

```

## License

MIT - Suhendra Ahmad