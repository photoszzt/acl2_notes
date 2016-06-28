# data types
- Number
    - integer, rational and complex number
- charaters
- strings
    - characters in "string quotes"
- symbols
    - sequence of alphabetical characters, digits, and/or certain signs (specifically, +, -, 
    *, /, =, <, >, ?, !, $, &, and _(underscore))
    - case unimportant
- pairs
    - pairs are called conses
    - no-conses are called atoms
    - left component, car
    - right component, cdr
    - three conventions
        - Nil can be written ()
        - A pair of the form (x . nil) may be written (x).
        - A pair of the form (x . (y...)) may be written (x y ...).
## Identity
cononical form:
- integers: base 10, drop leading 0s and + sign
- symbols: upper case
- conses: 
    - eschew the use of the three conventions noted above
    - use dot exclusively

# Terms
a term can be:
- a variable
- a quoted constant
- a function application written as a sequence, enclosed in parenthesis, consisting
of a function symbol of arity n followed by n terms. 



