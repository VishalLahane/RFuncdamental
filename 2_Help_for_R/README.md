# Built -in Help

- Help() to look at R documentation.
- Demo() to see demonstrations.
- Vignette() to get additional documentation.

### help
```
> help(rnorm) # search exact term
> ?rnorm # exact term search
> example(rnorm) # use example in doc
> help.search("rnorm") # search similer terms
> ??rnorm # search similer terms
```

### demo
```
> demo()  # list of all demo
> demo(package = .packages(all.available = TRUE))  # List if all package having 

> demo(package = 'graphics')  # show demo list from graphics

> head(demo(graphics)) # shows demo from graphics package press enter 
```

### Vignette ( documentation pdf)
```
> vignette()  # List of all Vignette packages
> vignette(package = .packages(all.available = TRUE))  # List if all  Vignette package having 

> vignette(package='parallel')

> vignette('parallel',package = 'parallel') # shows pdf in window
```

### Blogs
```
https://www.r-bloggers.com/
https://blog.revolutionanalytics.com/
https://www.r-statistics.com/
http://www.rdatamining.com/
```