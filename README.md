# Typo

### Phuuque up your input deliberatly, and/or intelligently.

![alt text](https://raw.githubusercontent.com/blanketcat/typo/master/assets/img/typos_matrix.png)

### Usage:

```~# typo --options "Your phrase." >> possible_pwords.txt```


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


### Vice Iteration.

*If you comp-sci college types have a name for this already, and there is an implementation in C or Python, file an issue and let me know the name of what I'm looking for new friend! :D*

with 2 threads:

```
0000 ---> ffff

0001 ---- ffff
0002 ---- fffe
0003 ---- fffd
  |        |
 ...      ...
  |        |
cfff ---- d000
```

with 4 threads:

```
0000 ---- 4000 ---- bfff ---- ffff
0001 ---- 4001 ---- bffe ---- fffe
0002 ---- 4002 ---- bffd ---- fffd
  |         |        |         |
 ...       ...      ...       ...
  |         |        |         |
3fff ---- 7fff ---- 8000 ---- c000
```

##### Disclaimer:

Typo is provided as is... and you're welcome, or whatever... :D

