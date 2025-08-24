# tee

ใช้เป็นการ redirection ได้ โดยใช้ร่วมกับ pipe ซึ่งจะมีการ print stdout ออกมาด้วย

```
export CATO="FireFish"
echo $CATO | tee meow.txt
  FireFish

cat meow.txt
  FireFish
```