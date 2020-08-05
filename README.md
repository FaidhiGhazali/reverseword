# reverseword

## Using For Loop

```
reverseWords (str) {
 var newString = "";
    for (var i = str.length - 1; i >= 0; i--) {
        newString += str[i];
    }
    return newString;
}

```

## Using Built-In Method

```
reverseWords (str) {
 return str.split("").reverse().join("")
}

```

## Using Spread Syntax & Built-In Method Array

```
reverseWords (str) {
 return [...str].reverse().join("")
}

```
