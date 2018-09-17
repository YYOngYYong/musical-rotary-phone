# 201809009 프로그래밍 첫날 Python 기초(문자열 관련 함수)

#### 문자 개수 세기(count)
  ---- 문자열 내에서 해당 문자의 개수를 알려준다
  ```python
a = "apple"
a.count(p)
  # 2

```
#### find와 index의 차이
```python
a = 'apple'
a.find(p)
# 1
a.index(p)
# 2
```
**'index'는 찾는 값이 문자열에 존재하지 않을 경우 '-1'을 도출, 'find'는 찾는 값이 존재하지 않는 경우 오류 발생**

#### 문자열 바꾸기(replace)
````python
a = "Life is too short, We need Python!"
a.replace('Life', 'Your leg)
# "Your leg is too short, We need Python"

````
#### 문자열 나누기(split)
```python
a = "Life is too short."
b = a.split()
print(b)
# ['Life', 'is', 'too', 'short']
```