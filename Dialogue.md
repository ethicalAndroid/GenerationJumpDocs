## General
Expressions, characters, and animation events are triggered by using tags.

Payloads are used as regular lines that are not displayed in regular speech text.

Choices can have conditions by using the tags.
## Conditions
The tags must be in the same scope as the text to count.

Example: `* [Trade the coin. #r:Coin]`

`#resource:KeyItem` Player must have resource (KeyItem)

`#trust:Farmers:5` Trust of (Farmers) must be >= (5).

`#story:Plotline:1` Story of (Plotline) must be >= (1).

`#and` Boolean And

`#or` Boolean Or

`#not` Boolean Not

Boolean operations on the right take precedence.

Example: `(true) #and (false) #or (true)` is true.

You can use the initial letter to indicate keywords:

Examples: `#r:KeyItem`, `#t:Farmers:5`, `#s:Plotline:1`, `#a`, `#o`, `#n`
## Payloads
`:collect:KeyItem` Player collects the resource (KeyItem)

`:drop:KeyItem` Player drops the resource (KeyItem)

`:increasetrust:John:5` Player increases trust with (John) by (5)

`:losetrust:John:5` Player loses trust with (John) by (5)

`:readstory:Plotline:1` Player continues the story (Plotline) by (1)

You can use the initial letter to indicate keywords:

Examples: `:c:KeyItem`, `:d:KeyItem`, `:i:John:5`, `:l:John:5`, `:r:Plotline:1`
