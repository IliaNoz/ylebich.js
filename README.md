# ylebich.js

Check the only truth about you, inspired by Heisenberg.

![PyPI](https://img.shields.io/pypi/v/vaccination)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/vaccination)
![PyPI - Downloads](https://img.shields.io/pypi/dm/vaccination)
![PyPI - License](https://img.shields.io/pypi/l/vaccination)

![Heisenberg](./.github/assets/heisenberg.png)

## Installation
```bash
$ npm install ylebich-js
```

## Usage

```js
const { YleBich } = require("ylebich-js");

const zuriko = new YleBich("Zuriko");
const iliko = new YleBich("Iliko");
const temuri = new YleBich("Temuri")

console.log(zuriko.sayMyName());
console.log(iliko.sayMyName());
console.log(temuri.sayMyName());
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for details.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors

- [**Temuri Takalandze**](https://abgeo.dev) - *Initial work*

## License

Copyright © 2021 [Temuri Takalandze](https://abgeo.dev).
Released under the [MIT](LICENSE) license.
