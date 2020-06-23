`+=` adds to the existing text

`'a' + '\_b'`

results in `a_b`

also could use es6 backticks:

```javascript
morseText += ` ${code[insertedInput[i].toLowerCase()]}`;
```

Or

```javascript
morseText = `${morseText} ${code[insertedInput[i].toLowerCase()]}`;
```

all give same result
