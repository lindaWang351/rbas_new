# t_hash Database structure

Use file structure.

## 1. time domain

1. /yyyy/mmm/d00/h00/c0000/rs0/ps000
1. /2020 /m00 /d01 /h00 /c0000 /rs0 /ps000
1. data in every year will be put into a new data base block

json file format of t_hash stored in the file.

```json
[{"ts":null, "t-hash":null }...]
```

## 2. code domain

1. /yyyy/h000-255/h000-255/h000-255
1. max file size is 1000 t_hash
1. additional levels of directory will be added when file > 1000 t_hash
1. data in every year will be put into a new data base block

```json
[{"t-hash":null, "time":null }...]
```
