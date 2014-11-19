Syntax highlighting and code snippets for [Spider language](http://spiderlang.org/).


Installation
============
On Windows: download/clone whole repository into folder: `%APPDATA%/Roaming/Sublime Text 3/Packages/SpiderScript`.


Snippets
========

Snippets in Sublime Text 3 are triggered by TAB key when cursor is blinking after snippet shortcut.

Functions
------------------
`f` => `(args) -> { SELECTED_TEXT }`

`fun` => ``

`funext` => `func Function1(args) extends Function2(args) { ... }`


Loops
-----

`for` =>
```
for var i = 0; i < Things.length; i++ {
	Things[i]
};
```

or *Improved Native For-Loop*:

```
for var i = Things.length - 1; i >= 0; i-- {
	Things[i]
};
```

`forin` =>
```
for item in items {
	item
}
```

`forinkv` =>
```
for key, value in items {
	value
}
```

`forof` => 
```
for key of object {
	key
}
```

`forofkv` =>
```
for key, value of object {
	value
}
```

`forlist` => `[expr for value in list]`

`forlistin` => `[expr for value in list if if-expr]`


Conditions
----------

`if` => `if true {}`

`ife` => 
```
if true {
    SELECTED_TEXT
}
else {

}
```

`ifin` =>
```
if key in object {
	
}
```


Objects
-------
`:` => `key: "value"`

`in` => `key in object`

`:f` => 
```
method_name: (attribute) -> {
	
},
```

`:,` => `value_name:value,`


Others
------
`timeout` => `setTimeout(() -> {}, 10);`