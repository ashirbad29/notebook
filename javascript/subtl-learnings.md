# javascript tips hacks learnings

### eleminate decimals without killing performance

```
Math.floor(Math.random() * 1000)

// better way
~~ (Math.random() * 1000)
/* ⚠ does't work with -ve intergers */

```

### Deleting array elements

```const numbers = [1, 2, 3, 4]
numbers.length = 0;
console.log(numbers) // []
```
