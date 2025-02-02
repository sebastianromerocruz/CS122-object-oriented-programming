<h1 align=center>Helpful Class Methods</h1>

---

## Sections

1. [**`Math` Class**](#1)
2. [**`Character` Class**](#2)
3. [**`String` Class**](#3)

---

<a id="1"></a>

## `Math` Class

**Usage**:

```java
Math.method()
```

| Method | Description |
|-|-|
| `sin(angle)` | Returns the trigonometric sine of an angle in radians. |
| `cos(angle)` | Returns the trigonometric cosine of an angle in radians. |
| `tan(angle)` | Returns the trigonometric tangent of an angle in radians. |
| `toRadians(angle)` | Converts an angle measured in degrees to an approximately equivalent angle measured in radians. |
| `toDegrees(angle)` | Converts an angle measured in radians to an approximately equivalent angle measured in degrees. |
| `asin(sine)` | Returns the angle in radians for the inverse of sine. |
| `acos(cosine)` | Returns the angle in radians for the inverse of cosine. |
| `atan(tangent)` | Returns the angle in radians for the inverse of tangent. |
| `atan2(y, x)` | Returns the angle in radians between the positive x-axis and the point `(x, y)`. |

| Method | Description |
|-|-|
| `exp(x)` | Returns `e` raised to the power of `x` (e<sup>_x_</sup>). |
| `log(x)` | Returns the natural logarithm of `x` (ln(_x_)). |
| `log10(x)` | Returns the base-10 logarithm of `x` (log<sub>10</sub>(_x_)). |
| `pow(a, b)` | Returns `a` raised to the power of `b` (a<sup>b</sup>). |
| `sqrt(x)` | Returns the square root of `x` for `x >= 0`. |
| `cbrt(x)` | Returns the cube root of `x`. |
| `hypot(x, y)` | Returns the square root of (x<sup>2</sup> + y<sup>2</sup>), without intermediate overflow or underflow. |

| Method | Description |
|-|-|
| `ceil(x)` | Rounds `x` up to the nearest whole number and returns a _double_. |
| `floor(x)` | Rounds `x` down to the nearest whole number and returns a _double_. |
| `round(x)` | Rounds `x` to the nearest whole number and returns a _long_ (for float input) or _int_ (for double input). |
| `abs(x)` | Returns the absolute value of `x`. |
| `max(a, b)` | Returns the maximum of `a` and `b`. |
| `min(a, b)` | Returns the minimum of `a` and `b`. |
| `random()` | Returns a pseudo-random `double` between `0.0` (inclusive) and `1.0` (exclusive). |
| `a + (int) (Math.random() * b)` | Returns a random integer between `a` and `a + b - 1`. |

<br>

<a id="2"></a>

## `Character` Class

**Usage**:

```java
Character.method()
```

| Method | Description |
|-|-|
| `isDigit(ch)` | Returns `true` if `ch` is a digit (0-9). |
| `isLetter(ch)` | Returns `true` if `ch` is a letter (A-Z, a-z). |
| `isLetterOrDigit(ch)` | Returns `true` if `ch` is a letter or digit. |
| `isLowerCase(ch)` | Returns `true` if `ch` is a lowercase letter. |
| `isUpperCase(ch)` | Returns `true` if `ch` is an uppercase letter. |
| `toLowerCase(ch)` | Converts `ch` to lowercase, if applicable. |
| `toUpperCase(ch)` | Converts `ch` to uppercase, if applicable. |
| `isWhitespace(ch)` | Returns `true` if `ch` is a whitespace character. |

<br>

<a id="3"></a>

## `String` Class

**Usage**:

```java
String string = "example";
string.method();
```

| Method | Description |
|-|-|
| `length()` | Returns the number of characters in the string. |
| `charAt(index)` | Returns the character at the specified `index`. |
| `concat(s)` | Returns a new string that concatenates this string with `s`. |
| `toLowerCase()` | Returns a new string with all characters in lowercase. |
| `toUpperCase()` | Returns a new string with all characters in uppercase. |
| `trim()` | Returns a new string with whitespace characters removed from both ends. |
| `substring(beginIndex, endIndex)` | Returns a substring from `beginIndex` (inclusive) to `endIndex` (exclusive). |
| `replace(oldChar, newChar)` | Returns a new string with all occurrences of `oldChar` replaced by `newChar`. |
| `split(regex)` | Splits the string around matches of the given regex and returns an array of substrings. |
| `indexOf(str)` | Returns the index of the first occurrence of `str` or `-1` if not found. |
| `lastIndexOf(str)` | Returns the index of the last occurrence of `str` or `-1` if not found. |
| `contains(str)` | Returns `true` if the string contains `str`. |
| `startsWith(prefix)` | Returns `true` if the string starts with `prefix`. |
| `endsWith(suffix)` | Returns `true` if the string ends with `suffix`. |
| `equalsIgnoreCase(str)` | Compares two strings, ignoring case differences. |

<!-- ---

### `Arrays` Class

**Usage**:

```java
import java.util.Arrays;
Arrays.method();
```

| Method | Description |
|-|-|
| `sort(array)` | Sorts the array in ascending order. |
| `binarySearch(array, key)` | Returns the index of `key` in a sorted array, or `-1` if not found. |
| `fill(array, value)` | Fills the array with the specified `value`. |
| `copyOf(array, newLength)` | Returns a new array with a specified length, copying elements from the original. |
| `copyOfRange(array, from, to)` | Returns a new array that is a copy from `from` (inclusive) to `to` (exclusive). |
| `toString(array)` | Returns a string representation of the array. |

---

### `ArrayList` Class

**Usage**:

```java
import java.util.ArrayList;
ArrayList<Type> list = new ArrayList<>();
list.method();
```

| Method | Description |
|-|-|
| `add(element)` | Adds `element` to the end of the list. |
| `add(index, element)` | Inserts `element` at the specified `index`. |
| `get(index)` | Returns the element at `index`. |
| `set(index, element)` | Replaces the element at `index` with `element`. |
| `remove(index)` | Removes the element at `index`. |
| `size()` | Returns the number of elements in the list. |
| `clear()` | Removes all elements from the list. |
| `contains(element)` | Returns `true` if the list contains `element`. |
| `indexOf(element)` | Returns the index of `element` or `-1` if not found. | -->