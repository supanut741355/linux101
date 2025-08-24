# Compressing

บีบอัดไฟล์ใน linux มี 3 เจ้า

1. bzip2 
    ```
      bzip2 <file_name>
    ```

2. gzip
    ```
      gzip <file_name>
    ```

3. xz
    ```
      xz <file_name>
    ```



# Uncompressing

ใช้ un

1. bunzip2 
    ```
      bunzip2 <compressed_file_name>
    ```

2. gzip
    ```
      gunzip <compressed_file_name>
    ```

3. unxz
    ```
      unxz <compressed_file_name>
    ```


# อ่านไฟล์โดยไม่ต้อง uncompress

1. zcat
    ```
      zcat <compressed_file_name>
    ```

2. bzcat
    ```
      bzcat <compressed_file_name>
    ```

3. xzcat
    ```
      xzcat <compressed_file_name>
    ```