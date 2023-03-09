
# Simple sass structure with compiler

Simple SASS structure for smaller projects with sass node package.


## Installation

Install with npm

```bash
  npm install --save-dev
```
    
## Usage

### For development process.
This command creates css file and source map.

```bash
  npm run sass:watch
```

### Build for production
This command creates a compressed css file

```bash
  npm run sass:release
```
## Sass folders structure

A simple structure of scss folders and files created as a base to start projects.

```bash
  our-project-name/
├── sass/
│   ├── 01-base/
│   │   ├── _breakpoins.scss
│   │   ├── _colors.scss
│   │   ├── _index.scss
│   │   ├── _mixins.scss
│   │   ├── _reset.scss 
│   │   └── _typography.scss 
│   ├── 02-components/
│   │   ├── _buttons.scss
│   │   └── _index.scss
│   ├── 03-layout/
│   │   ├── _footer.scss
│   │   ├── _forms.scss
│   │   ├── _header.scss
│   │   ├── _index.scss
│   │   ├── _navigation.scss
│   │   └── _sidebar.scss
│   ├── 04-pages/
│   │   ├── _home.scss
│   │   └── _index.scss
│   └── main.scss
├── node-modules/
├── package.json
├── style.css
└── style.css.map
```




Please write readable css. Use @use and @forward instead of @import. Stick to the BEM methodology. Use mixins and write DRY code.
Make web a better place ❤️🖥️

