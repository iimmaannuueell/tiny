# iimmaannuueell/tiny

Removes all spaces from a string.

## Installation

```bash
$ npm install @iimmaannuueell/tiny
```

## Usage

```python
const tiny = require("@iimmaannuueell/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)