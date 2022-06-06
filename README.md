## Anima design Tokens

## Project setup

1. Clone this repository

```sh
git clone git@github.com:AnimaApp/anima-design-tokens.git && cd anima-design-tokens
```

2. Install the dependencies

```sh
npm install
```

## How to install

```
yarn add -D @animaapp/anima-design-tokens
```

or

```
npm install --save-dev @animaapp/anima-design-tokens
```

## How to use

To use Anima's tokens, just need to import the main file

### ↳ With SCSS

```scss
/* since we use webpack you can just use ~ instead of 'node_modules/...' */

@import '~@animaapp/anima-design-tokens';
```

## What's in it?

- [x] Color shades
- [x] Fonts
- [x] Text sizes
- [ ] Semantic color tokens
- [ ] Shadows
- [ ] Border radius

## Release

1. Push a new package version

```
npm version vX.Y.Z
```

2. Push the changes

```
git push --follow-tags
```

3. Run on your terminal:

```
npm dist && npm publish
```
