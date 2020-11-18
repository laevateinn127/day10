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
  tuple使用, ()
  例1
t1 = ()
print(t1)
()
  例2
t2 = 1, 2 ,3
print(t2)
(1,2,3)
  例3
t3 = (1, 2, 3)
print(t3)
(1, 2, 3)
  例4
t3 = (1, 2, 3)
print(t3[0])
1
t3 = (1, 2, 3)
print(t3[1])
2
t3 = (1, 2, 3)
print(t3[2])
3
t3 = (1, 2, 3)
print(t3[3])
tuple index out of range
t3 = (1, 2, 3)
print(t3[-1])
3
t3 = (1, 2, 3)
print(t3[-2])
2
t3 = (1, 2, 3)
print(t3[-3])
1
t3 = (1, 2, 3)
print(t3[-4])
tuple index out of range
    例五
t3 = (1, 2, 3)
a, b, c= t3
print('a=', a, ',b=', b, ',c=', c)
a= 1 ,b= 2 ,c= 3
     例6
 a = 10
b = 20
print('交換前','a=', a, ',b=', b)
a, b = b, a
print('交換後','a=', a, ',b=', b)
交換前 a= 10 ,b= 20
交換後 a= 20 ,b= 10

a = '蘿蔔'
b = '大蒜'
c = '空格'
c = a#左傳右
a = b
b = c 
print(a,b)
大蒜 蘿蔔
    例7
t4 = (1,2,3,4)
t5 = (t4,5,6)
print(t5)
print(len(t5))#個數多寡(len)
print(t5[0][0])
((1, 2, 3, 4), 5, 6)
3
1
    例8

t6 = ('z', )
print(t6)
('z',)
```
```
shoplist1 = ['牛奶', '蛋', '咖啡豆', '西瓜', '鳳梨']
print('購物清單shoplist1為')
print(shoplist1)
購物清單shoplist1為
['牛奶', '蛋', '咖啡豆', '西瓜', '鳳梨']
list使用[],
shoplist2 = ['牛奶', '蛋', '咖啡豆', '西瓜', '鳳梨']
print('顯示shoplist2[0]為',shoplist2[0])
顯示shoplist2[0]為 牛奶
shoplist3 = ['牛奶', '蛋', '咖啡豆', '西瓜', '鳳梨']#以影號框住為一字元
print('購物清單shoplist3的長度為', len(shoplist3))
購物清單shoplist3的長度為 5

shoplist = ['牛奶', '蛋', '咖啡豆', '西瓜', '鳳梨']
shoplist[1] = '皮蛋'
print("執行 shoplist[1] = '皮蛋' 後")
print(shoplist)
執行 shoplist[1] = '皮蛋' 後
['牛奶', '皮蛋', '咖啡豆', '西瓜', '鳳梨'
```
