# Arrays

### Sort array

```text
const numbers = [10, 7, 2901, 3.5];
numbers.sort((a, b) => a - b); // ascending
```

### Bubble sort

```text
const bubbleSort = arr => { let sorted;
  do { sorted = false;
    for (let i = 0; i < arr.length - 1; i += 1) {
      if (arr[i] > arr[i + 1]) {
        const temp = arr[i]
    
        arr[i] = arr[i + 1]
        arr[i + 1] = temp;
    
        sorted = true
      }
    }
  } while (sorted)
  return arr;
}
```





