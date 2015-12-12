# remove-accents

Removes the accents from a string, converting them to their corresponding non-accented ASCII characters.

## About

An easy to use solution for converting all accented characters to their corresponding non-accented ASCII characters.

## Syntax

``` js
removeAccents(inputString)
```

#### inputString

The string that you wish to remove accents from.

## Usage

Call `removeAccents()` by passing the string you wish to remove accents from, and you will get the non-accented string as result.

``` js
var input = 'ÀÁÂÃÄÅ';
var output = removeAccents(input);

console.log(output); // AAAAAA
```

## License

MIT