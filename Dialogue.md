## General
Expressions, characters, and animation events are triggered by using tags.



Choices can have conditions by using the tags.

The tags must be in the same scope as the text to count.

Example: `* [Trade the coin. #r:Coin]`

## Conditions
`resource:KeyItem` Player must have resource (KeyItem)

`trust:Farmers:5` Trust of (Farmers) must be >= (5).

`story:Plotline:1` Story of (Plotline) must be >= (1).

`and` Boolean And

`or` Boolean Or

`not` Boolean Not

Boolean operations on the right take precedence.

Example: `true and false or true` is true.

You can use the initial letter to indicate keywords:

Example: `r:KeyItem`, `t:Farmers:5`, `s:Plotline:1`, `a`, `o`, `n`

