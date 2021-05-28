### Merging two dicts in Python 3.5+ with a single expression:

```
x = {'a': 1, 'b': 2}
y = {'b': 3, 'c': 4}

z = {**x, **y}

print(z)

# Result:
# {'c': 4, 'a': 1, 'b': 3}
```

### Merging two dicts in Python 2.x with a single expression:
```
x = {'a': 1, 'b': 2}
y = {'b': 3, 'c': 4}

z = dict(x, **y)

# Result:
# {'c': 4, 'a': 1, 'b': 3}
```

---

In these examples, Python merges dictionary keys in the order listed in the expression, overwriting duplicates from left to right.

See: https://www.youtube.com/watch?v=Duexw08KaC8
