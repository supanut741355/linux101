# Grep

**"ใช้หาข้อความที่อยู่ในไฟล์"**

ใช้ในการ print line ของ file ที่ match กับ pattern

syntax
  ```
    grep <pattern> <file>
  ```

eg. มีไฟล์ sample.txt และต้องการ search match pattern line.
  ``` 
    grep line ./sample.txt

      This is the first line. 
      Followed by the seconds line.
      And then the third line.
  ```


  ```
    grep exam example.txt

      (ถ้ามีอักษรประกอบอยู่ให้เอาด้วย)
      grep examples
      linux exam on 19th
  ```


### Add-on flag

-w 
    ```
      grep -w exam example.txt

      (ต้องมีอักษรครบเท่านั้นถึงจะเอา)
      linux exam on 19th

    ```