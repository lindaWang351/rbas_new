# t_hash Database structure

Use file structure.

## 1. time domain

1. /yyyy/mmm/d00/h00/c0000/rs0/ps000
1. /2020 /m00 /d01 /h00 /c0000 /rs0 /ps000
1. data in every year will be put into a new data base block

json file format of t_hash stored in the file.

```json
[{"ts":"ts-server-ID", "t-hash":"64*hex" }...]
```

## 2. code domain

1. /yyyy/h000-255/h000-255/h000-255
1. the first 3 bytes of hash will used for directory name.
1. max file size is 1000 t_hash
1. additional levels of directory will be added when file > 1000 t_hash
1. data in every year will be put into a new data base block

```json
[{"t-hash":"64*hex", "time":"utc" }...]
```
