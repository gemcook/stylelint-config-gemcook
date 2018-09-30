# stylelint-config-gemcook

## Usage

### Install:

#### `npm`

```sh
npm install --save-dev \
  stylelint-config-gemcook \
  stylelint-config-recess-order \
  stylelint-prettier \
  prettier \
  stylelint
```


#### `yarn`

```sh
yarn add --dev \
  stylelint-config-gemcook \
  stylelint-config-recess-order \
  stylelint-prettier \
  prettier \
  stylelint
```

### Configure

Then create a file named `.stylelintrc` with following contents in the root folder of your project:

```js
{
  "extends": ["stylelint-prettier/recommended", "stylelint-config-recess-order"]
}
```
