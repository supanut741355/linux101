# Pipe

use to linking multiple command 

use output of 1st command to be input of 2nd command

```
command_1 | command_2
```

eg.
```
cat sameple.txt
  Hello there!
  Nice to see you here!


grep Hello sample.txt > file.txt

less file.txt
  Hello there!
  file.txt (END)
```


```
grep Hello sample.txt | less
  Hello there!
  (END)


less sample.txt
  Hello there!
    Nice to see you here!
  sample.txt (END)
```