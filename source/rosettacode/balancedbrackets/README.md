# Rosettacode: Balanced brackets in Ceylon

[http://rosettacode.org/wiki/Balanced_brackets#Ceylon](http://rosettacode.org/wiki/Balanced_brackets#Ceylon)

## Task description

* Generate a string with N opening brackets (“[”) and N closing brackets (“]”), in some arbitrary order.

* Determine whether the generated string is balanced; that is, whether it consists entirely of pairs of opening/closing brackets (in that order), none of which mis-nest.


## Implementation

**Code:**
[run.ceylon](run.ceylon)

**Output:**

                         - OK
    []                   - OK
    ][[]                 - NOT OK
    ][[]][               - NOT OK
    []]][[][             - NOT OK
    [[[][][]]]           - OK
    [[][]][[]][]         - OK
    [[][[[]]][]][]       - OK
    ]][[][][[][]][[]     - NOT OK
    [[]]]]]]][[[[][][[   - NOT OK
    [[]][[]][[]]]][[[]][ - NOT OK
