# reverseword

```
reverseWords (str) {
  let arr = ''
  let str1 = str.match(/\S*/g)
  for(let i=0;i<str1.length;i++) {
    arr += str1[i].split('').reverse().join('') + ' '
  }
  return arr
}

```
