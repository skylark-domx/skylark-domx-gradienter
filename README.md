# skylark-gradx
A version of gradX that ported to running on skylarkjs

## Dependences

| Project                                                      | Status | Description                                           |
| ------------------------------------------------------------ | ------ | ----------------------------------------------------- |
| [skylark-langx](https://github.com/skylark-langx/skylark-langx) |        | Javascript language extension library                 |
| [skylark-graphics-color](https://github.com/skylark-graphics/skylark-graphics-color) |        | The color util library |
| [skylark-spectrum](https://github.com/skylark-integration/skylark-spectrumr) |        | The color picker                                      |

## Different builds

builds are in the directory dist.

|                      | build                                     | Description              |
| -------------------- | ----------------------------------------- | ------------------------ |
| full                 | skylark-gradx-all.js              | included dependences     |
| only                 | skylark-gradx.js                  | not included dependences |
| full （development） | uncompressed/skylark-gradx-all.js | included dependences     |
| only （development） | uncompressed/skylark-gradx.js     | not included dependences |

Please use the "full" version when using this library alone, and use the "only" version when using other skylark libraries.

## Installation

You can get the latest version in many different ways:

- Downloading [a ZIP file from master](https://github.com/skylark-integration/skylark-gradx/archive/master.zip)
- Cloning using Git: `git clone https://github.com/skylark-integration/skylark-gradx.git`
- Installing via NPM: `npm install https://github.com/skylark-integration/skylark-gradx.git#master --save`

## Building 

- Ensure that Node.js is installed.
- Run npm install https://github.com/skylarkjs/skylark.git -g to ensure skylark sdk is installed.
- Run npm install to ensure the required dependencies are installed.
- Run npm run build. The builds will be placed in the dist/ directory.

## License

Released under the [MIT](http://opensource.org/licenses/MIT)