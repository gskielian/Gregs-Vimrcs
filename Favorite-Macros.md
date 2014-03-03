Macros
======


These simple macros save me tons of time.  

How to get them
---------------

To get use these, simply paste them into a vim file then execute (in normal mode) make sure your cursor is on the line before executing:


```vim
"gyy
```

The above command sets register "g" to be the macro beneath -- I use this with the following git macro.


List of Macros
--------------

* `git add * && git commit` macro (useful for everything)

```vim
:!git add * && git commit
```



* make underline macro (useful for md)

```vim
"oyyj"oPVr-o
```

* Make a time stamp with hours minutes seconds only

```vim
:r!date | awk '{print $4}'
```

* Modded macro for logging

```vim
:r!date | awk '{print "* " $4}'
```
