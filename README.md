# Basic molar mass calculator
Very basic JS application.

Just write your formula and the molar mass will appear.

It uses the `molarcalc` node package ([more info here](https://github.com/draulpozas/molarcalc)).

It recognises:
- Elements (written as their periodic table symbols).
- Frequent o-chem abbreviations such as 'Me' for methyl or 'Ph' for 'phenyl' (will probably add some more in the future).
- Numbers.
- Parentheses surrounding several elements. It will read everything inside and add it to the calculation a number of times indicated by the number after the closing parenthesis. Just a complicated way of saying that it knows how to read parentheses.

It does NOT recognise:
- Words. Won't recognise 'tri-' or 'acetyl'.
- 'Ac' for 'acetyl', as it creates a conflict with element Actinium. You will need to write 'CH3CO', 'C2H3O', 'COMe', etc.
