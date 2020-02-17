awk -F ' ' '{sum += $COLUMN_NUMBER} END {print sum}' FILE_PATH

-F는 파일로부터

' ' 는 컬럼 구분자. ',' '|' ';'...

$COLUMN_NUMBER가 문자열이면 더해지지 않음. 숫자만 더해진다.

```
# sample.log
a, a
1, 1
2, 2
b, b
c, c
3, 3
```
```sh
awk -F ' ' '{sum += $1} END {print sum}' sample.log
```
6
