# 你好

> 你真棒，你浏览了这个网站。你可以看到一个初中生编的发颠小程序
>
> 没错。（听说作者时不时会在网站上发颠）
>



# C语言整活

> [!WARNING]
>
> 禁止随意转载或商用

通过网盘分享的文件：计算器
链接: https://pan.baidu.com/s/18OJJ3f57k3g01zAmPN399Q 提取码: mawa





# 小工具

> [!WARNING]
>
> 禁止随意转载或商用

通过网盘分享的文件：提醒事件
链接: https://pan.baidu.com/s/1Uh5NeajKf1EMIWB5g3Zdwg 提取码: mawa

> [!IMPORTANT]
>
> 请安装pyqt库

通过网盘分享的文件：计算器
链接: https://pan.baidu.com/s/18OJJ3f57k3g01zAmPN399Q 提取码: mawa

# 游戏

> [!WARNING]
>
> 禁止随意转载或商用

通过网盘分享的文件：shootingblock
链接: https://pan.baidu.com/s/1HTMLNIm-1qJ0slcCyrz05A 提取码: mawa



# 作者github

[ja7827298/-: 写不下去了](https://github.com/ja7827298/-)



# 作者B站

名称：**理理茂茂**



# 作者抖音



名称：不会飞的大疆mini 2 se

# 开源项目计算器

```python

```

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "错误：除数不能为零"
    return x / y

def main():
    print("简单计算器")
    print("可用操作：加法 (+), 减法 (-), 乘法 (*), 除法 (/), 退出 (q)")

    while True:
        operation = input("请输入操作 (+, -, *, /, q): ").strip()
        if operation == 'q':
            print("退出计算器，再见！")
            break
    
        if operation not in ['+', '-', '*', '/']:
            print("无效的操作，请重新输入。")
            continue
    
        try:
            num1 = float(input("请输入第一个数字: "))
            num2 = float(input("请输入第二个数字: "))
        except ValueError:
            print("输入无效，请输入数字。")
            continue
    
        if operation == '+':
            result = add(num1, num2)
        elif operation == '-':
            result = subtract(num1, num2)
        elif operation == '*':
            result = multiply(num1, num2)
        elif operation == '/':
            result = divide(num1, num2)
    
        print(f"结果: {result}")

if __name__ == '__main__':
    main()
