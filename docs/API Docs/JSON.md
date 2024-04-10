icon: simple/json

# JSON - Cheat sheet

## Introduction

- stands for JavaScript Object Notation
- easy to read and write.
- language agnostic data-interchange format
- filename extension is .json
- Internet Media type is application/json

## Examples

```JSON
{
  "name": "Jason",                      //value is `string`
  "age": 39,                            //value is `number`
  "height": 1.92,                       //value is `number.fraction`
  "gender": "M",                        //value is `string`
  "salary": 70000,                      //value is `number`
  "married": true,                      //value is `number`
  "children": [                         //value is `array`
    {"name": "Tom", "age": 9, "gender":"M"},
    {"name": "Ava", "age": 7, "gender":"F"}
  ]
}
```

## Data Types

| Type    | Description                             |
| ------- | --------------------------------------- |
| String  | Series of characters                    |
| Number  | Double precision floating-point         |
| Boolean | true or false                           |
| Array   | Ordered sequence of values              |
| Value   | String, Number, Boolean, null etc       |
| Object  | Unordered collection of key/value pairs |
| null    | Null or Empty                           |

## String

| Symbol | Description                |
| ------ | -------------------------- |
| `"`    | Double quote               |
| `\`    | Backslash                  |
| `/`    | Forward slash              |
| `\b`   | Backspace                  |
| `\f`   | Form feed                  |
| `\n`   | Newline                    |
| `\r`   | Carriage return            |
| `\t`   | Tab                        |
| `\u`   | Trailed by four hex digits |

## Number

| Type     | Description                            |
| -------- | -------------------------------------- |
| Integer  | Digits 1-9, 0 and positive or negative |
| Fraction | Fractions like 0.3, 3.9                |
| Exponent | Exponent like e, e+, e-, E, E+, E      |
