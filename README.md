# day10
```
'a' = 芭樂
'b' = 芒果
'c' = 龍眼
'd' = 香蕉
'e' = 火龍果
for x in range(1,10):
  print('a,b,c,d,e',end='')
  ```
  ```
  for a in range(1,10):
  for b in range(10,a,-2):
    print(' ',end='')
  for c in range(1,b):
    print('$',end='')
  print(' ')
  ```
