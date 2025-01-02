# So sánh Python và C/C++
|              |     Python    |        C/C++        |
|--------------|---------------|---------------------|
| Kiểu dữ liệu | K cần khai báo|Cần khai báo rõ ràng |
|              | Thông dịch    |Biên dịch            |
|Quản lý bộ nhớ|Tự động        |new/ delete          |


# Cấu trúc của 1 project
- Với các project nhỏ, viết trực tiếp.

- Với các project lớn và cần mở rộng:
```
import

def main():

if __name__ == "__main__"
```

`if __name__ == "__main__` sẽ kiểm tra file hiện tại có được chạy trực tiếp không. Khi file import vào 1 module khác, đoạn mã trong `if __name__ == "__main__` sẽ không được thực thi.

- Hướng dẫn chia module
**module1.py**
```
def greet():
    #code

if __name__ == "__main__":
    print("Module 1 is running")
```

**module2.py**
```
def cal():
    #code

if __name__ == "__main__":
    print("Module 2 is running")
```

**main.py**
```
import module1
import module2

def main():
    #code

if __name__ == "__main__":
    main()
```

# 1. Print & Variables
- Hàm Print: in ra màn hình console
print("*string*"): in chuỗi
print(x): in biến x, x có thể là int hoặc str

Example:
```
x = "John"
y = "Ryan"
z = 5
print(x)
print(x + y)
print(z)
print(x + z) #báo lỗi, dùng + thì phải cùng kiểu, nếu cùng là int => KQ phép cộng, cùng là str => Chuỗi
print(str(z) + x) #ép kiểu z về thành str
```
output:
```
John
JohnRyan
5
5John
```

- F string
`print(f"{x} {y}")`

- Nhập chuỗi: input("")
+ Cách 1:
```
ip = nput("What is the target ip?") 
#Chỉ cho nhập chứ không in KQ
#Để in KQ kết hợp hàm printf
print("The ip you entered is " + ip)
```

+ Cách 2:
`print("Your target is " + input("What is the target ip? "))`

# 2. Data Types
Using type() to find out the type of the data.

**2.1. string**
`print(type("Hello World"))`

- In ký tự bất kỳ trong chuỗi, dùng [num]
`print("Hello world"[0])`
=> output: H

**2.2. interger**
`print(type(5))`

**2.3. float**
`print(type(5.67))`

**2.4. boolean**
true or false

# 3. If statements
if:
elif:
else:

# 4. For loops
```
fruits = ["apple", "banana", "cherry"]

for i in fruits:
    print(i)
```

```
for i in range (1,10):
    print(i)

#có thể thêm bước nhảy ở range để in toàn số chẵn, hoặc lẻ

for i in range(0,100,2):
	print(i)
```

# 5. Functions
def function_name():

# 6. Recon tools for cyber security

# 7. python for Linux
pycharm

# 8. pass through data
Chuyển tiếp dữ liệu mà không biến đổi
