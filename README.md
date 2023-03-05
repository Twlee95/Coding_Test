# Coding_Test

### 문자열 my_string과 정수 num1, num2가 매개변수로 주어질 때, my_string에서 인덱스 num1과 인덱스 num2에 해당하는 문자를 바꾼 문자열을 return 하도록 solution 함수를 완성해보세요.

##### 문자열 중 특정 인덱스의 문자를 바꾸는 방법

```python
a = "abc"
a= list(a)
a[0] ='b'
''.join(a)
```


### 7의 개수

##### 2차원 리스트를 1차원으로 바꾸는 방법
```python
list1 = [[1, 10], [2, 22], [3, 19], [4, 7]]
list2 = sum(list1, [])
print(list2)
```

### 문자열 계산하기

##### eval 함수의 쓰임
```python
# 1. 문자열 덧셈
a = eval('"BlockDMask" + "blog"')
print(f"1. eval('\"BlockDMask\"' + '\" blog\"') : {a}")
 
# 2. 숫자 덧셈
b = eval("100 + 32")
print(f'2. eval("100 + 32") : {b}')
 
# 3. 내장 함수 abs
c = eval("abs(-56)")
print(f'3. eval("abs(-56)") : {c}')
 
# 4. 리스트 길이
d = eval("len([1,2,3,4])")
print(f'4. eval("len([1,2,3,4])") : {d}')
 
# 5. round 함수
e = eval("round(1.5)")
print(f'5. eval("round(1.5)") : {e}')
```
