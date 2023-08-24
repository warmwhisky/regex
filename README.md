# Regex

## Allow Everything
Except spaces
```regex
^[^ ]+$
```

Except spaces & new lines
```regex
^[^\n ]+$
```

Except the word "hello"
```regex
^[^hello]+$
```

## Only Allow
Uppercase alphabets 
```regex
^[A-Z]+$
```

Numbers 
```regex
^[0-1]+$
```

Alphanumeric uppercase & lowercase and spaces
```regex
^[a-zA-z0-1 ]+$
```

Uppercase alphabets with hyphens and underscores
```regex
^[A-Z-_]+$
```

## String contains
Match a string in between another string
```regex
string
```










