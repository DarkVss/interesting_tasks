# Interesting for realization tasks 

## Array elements combinations

### Non unique combinations 

Element position in result combination is important for uniqualization its mean all possible variations without ignoring position

```php
$array = ["1", "2", "3"];
print_r(do_non_unique_combination(arrar:$array, separator:" "));

array(
    "1",
    "1 2",
    "1 3",
    "1 2 3",
    "1 3 2",
    "2",
    "2 1",
    "2 3",
    "2 1 3",
    "2 3 1",
    "3",
    "3 1",
    "3 2",
    "3 1 2",
    "3 2 1",
)
```

### Unique combinations 

Element position in result combination not is important for uniqualization its mean all possible variations with ignoring position

#### `String`

```php
$array = ["1", "2", "3"];
print_r(do_unique_combination(arrar:$array));

array(
    "1",
    "1 2",
    "1 3",
    "1 2 3",
    "2",
    "2 3",
    "3",
)
```

#### `Integer`

```php
$array = [1, 2, 4];
print_r(do_possible_sums(arrar:$array, separator:" "));

array(
    1,
    3,
    5,
    2,
    6,
    4,
    7,
)
```
