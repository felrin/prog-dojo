# Narcissistic Number

## EN

### Task
A narcissistic number is a number that is the sum of its own digits each raised to the power of the number of digits.
For example, take 153 (3 digits), which is narcisstic:
```
1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153
```
1652 (4 digits), is non-narcisstic:
```
1^4 + 6^4 + 5^4 + 2^4 = 1 + 1296 + 625 + 16 = 1938
```
Write a program which returns `true` or `false` depending upon whether the given `number` is a narcissistic number or not.

### Example
```
isNarcissistic(153) => true
isNarcissistic(370) => true
isNarcissistic(1652) => false
```

## HU

### Feladat
A nárcisztikus számok alatt olyan számokat értünk, amelyek egyenlőek a saját számjegyeinek a számjegyek számának hatványára emelésének összegével.
Például 153 (3 számjegy) egy nárcisztikus szám:
```
1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153
```
1652 (4 számjegy) nem nárcisztikus:
```
1^4 + 6^4 + 5^4 + 2^4 = 1 + 1296 + 625 + 16 = 1938
```
Írj egy programot, amely `true` (igaz) vagy `false` (hamis) értékkel tér vissza attól függően, hogy a `number` változó értéke nárcisztikus szám-e.

### Példa
```
isNarcissistic(153) => true
isNarcissistic(370) => true
isNarcissistic(1652) => false
```