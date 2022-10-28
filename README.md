# Emacs-doom-config


To activate mouse control in doom emacs

edit the file below : 

```~/.doom.d/init.el```

uncomment the line with tty to activate it !
```
       :os
       (:if IS-MAC macos)  ; improve compatibility with macOS
       ;;tty   
```

```
       :os
       (:if IS-MAC macos)  ; improve compatibility with macOS
       tty   
```

After that, 

you need to reopen emacs and make ```alt + x``` and type ```doom/reload``` and wait to doom emacs get and
install package. 

you're done ! you now have the mouse control in your emacs-nox 


for epitech student: (add the snippet hedear plugin to doom emacs) 

in ``` ~/.doom.d/config.el```

add the tow lines : 

```
(load! "epitech/std.el")
(load! "epitech/std_comment.el")
```

get the "epitech" folder in the repos and put it in : 


```~/.doom.d/```


