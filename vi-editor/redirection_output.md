# Redirection output

use " > ": redirect output to create / replace to file

```
export $DOG=Happy_and_Lucky
echo $DOG > dogo.txt

cat dogo.txt
  Happy_and_Lucky
```



append use " >> "
```
echo "Both is nice dog." >> dogo.txt

cat dogo.txt
  Happy_and_Lucky
  Both is nice dog.
```