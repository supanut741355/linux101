# Vi editor

syntax
```
  vi <path_to_file>
```

มี 3 mode
1. Command mode (เข้ามาจะเป็น mode นี้) -> ใช้ในการ copy, paste, delete

2. Insert mode -> ใช้ในการ edit, add, remove text

3. Last line mode  -> ใช้ในการ save file, discard change, exit vi

---

### Switch mode

mode_1 ไป mode_2 ใช้ i

mode_2 กลับ mode_1 ใช้ esc

mode_1 ไป mode_3 ใช้ :

mode_3 กล้บ mode 1 ใช้ esc

---

### Command mode

Hotkey
1. Copy a line -> y, y

2. Paste a copy line -> p

3. Delete a letter -> x

4. Delete line -> d, d

5. find string ->  /<string>    , หาตัวต่อไปใช้ n

6. คลุมหลาย file -> v

--- 

### Lastline mode

1. แสดง row -> :set number

2. save file + exit -> :wq

3. exit only -> :q!


