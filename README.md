[![NPM @latest](https://img.shields.io/npm/v/js-beautify-with-blade.svg)](https://www.npmjs.com/package/js-beautify-with-blade)
[![npm](https://img.shields.io/npm/dt/js-beautify-with-blade)](https://www.npmjs.com/package/js-beautify-with-blade)
![NPM](https://img.shields.io/npm/l/js-beautify-with-blade)
# JS Beautifier with blade

[![NPM stats](https://nodei.co/npm/js-beautify-with-blade.svg?downloadRank=true&downloads=true)](https://www.npmjs.org/package/js-beautify-with-blade)

This's a [js-beautify](https://github.com/beautify-web/js-beautify) fork but with full support to [Blade](https://laravel.com/docs/blade)

The whole idea behind this package to beautify the blade files such as html with all configrations & rules.
This package also support beautify js & css with the same API of original [js-beautify](https://github.com/beautify-web/js-beautify)
## Installation 

Install js-beautify-with-blade with npm globaly

```bash 
  npm -g install js-beautify-with-blade
```
or as a `node` library locally per project

```bash 
  npm install js-beautify-with-blade
```
## Usage

Beside all the usage examples you can found at the orignal [js-beautify](https://github.com/beautify-web/js-beautify).

You can use this package as blade beautifier
```bash
npx html-beautify resources/views/**/*.blade.php -r
```
run the above command in your project's root directory will beautify all the blade files


  
## Features

- Automatically Indents markup inside directives
- Automatically add spacing to blade templating markers
- Support all [HTML Beautifier Options](https://github.com/beautify-web/js-beautify#css--html)
- To remove the space between `@` and the directive set `space_after_directive` to `false`


  
## License

[MIT](https://choosealicense.com/licenses/mit/)

  
## Roadmap

- [x] Add indendt for `@case`
- [ ] Support single custom directive
- [x] Add options to customize space between `@` & directive

  
## Contributing

Contributions are needed and always welcome!
  
## Credits

### Orignal package Credits
- Created by Einar Lielmanis, einar@beautifier.io
- Command-line for node.js by Daniel Stockman daniel.stockman@gmail.com
- Maintained and expanded by Liam Newman bitwiseman@beautifier.io

Thanks also to Jason Diamond, Patrick Hof, Nochum Sossonko, Andreas Schneider, Dave Vasilevsky, Vital Batmanov, Ron Baldwin, Gabriel Harrison, Chris J. Shull, Mathias Bynens, Vittorio Gambaletta and others.

### Blade support
- Maintained and expanded by [Khaled Sadek](https://github.com/khaled-sadek)

Many thanks to [fzldn](https://github.com/fzldn) for the idea and his [gist](https://gist.github.com/fzldn/a27973ff7e4c8e3738b0e06e525f7403)