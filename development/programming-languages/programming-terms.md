# A
# B
# C
### Class
# D
# E
# F
# G
# H
### Higher order functions
Functions that accept other functions as parameters or return other functions.

```js
function f (x) {
    return x + 3;
};
function g (func, x) {
  return func(x) * func(x);
};

console.log(g(f, 7));


let f = (x) => x + 3;
let g = (func, x) => func(x) * func(x);

console.log(g(f, 7));
```

# I
### Inheritance
In [[programming-terms|Object-oriented programming]], inheritance is the mechanism of basing an object or [[programming-terms|Class]] upon  another object or class, retaining similar implementation.

```js
class Animal {
	sleep() {
		console.log('zZzZ')
	}
}

class Cat extends Animal {
	meow() {
		console.log('Meow')
	}
}

const cat = new Cat()

cat.meow() // Meow
cat.sleep() // zZzZ
```

# O
### Object-oriented programming