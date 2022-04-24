# WORDLE Algorithm
This is matching algorithm of WORDLE game. You can implement the algorithm to build your desired application.

## Basic Usage

```js
import { Wordle } from './wordle';

Wordle(guess, solution);
```

## Return Type
Returns an `Array`/`String[]` of the status of each letter of the guessed word comparing to the solution word.
- `'0'` : The letter is in correct position
- `'1'` : The letter is in present in the word, but not in position
- `'2'` : The letter is in absent in the word
