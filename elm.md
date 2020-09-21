- It has in the runtime some Json encoder/decoder for any elm type
 (this is how js types and elm types are converted one to another with ports),
 so why do I need to write my own JSon decoder/encoder ?
https://medium.com/@_rchaves_/elm-how-to-use-decoders-for-ports-how-to-not-use-decoders-for-json-a4f95b51473a

- It misses pattern matching with multiple patterns

- record update: {x | y = w} but x can only be a variable. Why?

- you cannot choose the names when destructuring a record, like {x = a, y = b}. Only {x, y}

- You cannot access the field of a js object. This is in particular a shame when trying to get the mouse relative position in an element. OffsetX/Y are relative to any sub-element that the mouse is over, but using the field currentTarget,
the relative position could be given. Unfortunately, this is not possible.
