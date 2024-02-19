![Furina](https://i.imgur.com/mgvEIuY.jpg)

# Installation

- You can install ironman-api using npm:

```bash
npm install ironman-api
```

## Usage
```txt
To use it simply require it in your code and call the relevant functions. Here's a basic example:
```
```js
const { genshinCH } = require('ironman-api');
```

### Example

- You can use https://pin.it and https://in.pinterest.com URLs

```js
const { pinterestdl } = require('ironman-api');

(async () => {
  console.log(await pinterestdl('https://in.pinterest.com/pin/617204323960160868/'));
})();
```

### Output
```json
{
   "ironman":{
      "url":"https://i.pinimg.com/736x/11/3a/4a/113a4af38e8eae9b500457071986782e.jpg",
      "title":"胡宮 -Komiya- (@komiya_latte) on X",
      "type":"image",
      "Creator":"IRON-M4N",
      "description":"劇場 "
   }
}
```

### Coming Soon
This package is under development, and many exciting features are planned for future releases. Stay tuned for updates and enhancements!

## Contributing

We welcome contributions! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. If you wanna contact me check my GitHub profile.

<h6> Copyright © 2024 IRON-M4N <br>
