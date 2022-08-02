# WORDLE Algorithm
This is matching algorithm of Wordle game in Javascript.

## Basic Usage

```js
import { check } from './wordle';

check(guess, solution);
```

## Return Type
Returns an `Array`/`String[]` of the status of each letter of the guessed word comparing to the solution word.
- `'0'` : The letter is in correct position
- `'1'` : The letter is in present in the word, but not in position
- `'2'` : The letter is in absent in the word
