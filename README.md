# Typo

### Phuuque up your input deliberatly, and/or intelligently.

![alt text](https://raw.githubusercontent.com/blanketcat/typo/master/assets/img/typos_matrix.png)

### Usage:

```~# typo --options "Your phrase." >> possible_misspellings.txt```


### Options:

```
--switched-chars 'the, hte, teh...'
--missed-chars 'Input: The => Out: Th, he'
--doubled-chars 'In: the => Out: tthe, thhe, thee'
--missed-spaces 'In: The string => Out: Thestring'
--switched-case 'In: the => Out: the, The, tHe, thE'
--caps-locked 'In: The => Out: tHE'
--wrong-chars 'In: the => Out: 5he, 6he, rhe, yhe, fhe, ghe, hhe, .. etc.'
--product [number] 'Cross product of all possible n-length char-combs of chars in string'
-r --recursive 'Recursively incorporates other options.'
```


### The Keymap Class

1) The keyboard is represented as 2 matrices. (UPPER and lower case)
2) The neighboring keys of each key in the matrices are determined on instantiation. (defaults to 'en_us' mapping)

*Looking for a list of international keyboard layouts w/ keycodes to append to, or replace this. If you know where that information is, make a pull request new friend! :D*
