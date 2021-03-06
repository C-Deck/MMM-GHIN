# Magic Mirror Module GHIN

The `GHIN` module is a <a href="https://github.com/MichMich/MagicMirror">MagicMirror</a> addon.
This module displays your official USGA handicap on your MagicMirror.

** This module currently is not working due to the use of ES6 style imports **

## How to use this module

1. Clone this repo with the following command: `git clone https://github.com/C-Deck/MMM-GHIN.git`
1. Install all the npm modules with either `yarn install` or `npm install`
1. Update your [Magic Mirror Config](https://github.com/MichMich/MagicMirror/blob/master/config/config.js.sample), by adding the following object:
   To use this module, add it to the modules array in the `config/config.js` file:

```javascript
modules: [
  {
    module: 'MMM-GHIN',
    position: 'bottom_bar',
    config: {
      ghinNumber: '00000000', // Your GHIN Number
      updateInterval: 37000, // update interval in milliseconds
    },
  },
]
```

## 🛠️ Config

- `module` the name of the module you are installing.
- `position` where you want the handicap value to appear
- `ghinNumber` Your specific GHIN Number
- `updateInterval` default is set to 5 minutes

## ✨ Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/C-Deck/mmm-ghin/issues)

## Author

**Clint Decker**

- [github](https://www.github.com/C-Deck)

### ⚖️ License

This project is licensed under the MIT License - see the LICENSE.md file for details
