# Redirection Error

use " 2> ": redirect error to create / replace to file

```
cat d.txt 2> d_error.txt

cat d_error.txt
  cat: d.txt: No such file or directory

```

append error use " 2>> "
```
cat dg.txt 2>> d_error.txt

cat d_error.txt
  cat: d.txt: No such file or directory
  cat: dg.txt: No such file or directory
``` 


