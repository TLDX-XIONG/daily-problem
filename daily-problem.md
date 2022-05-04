- ### 2022.4.29
  **题目描述**
  
    编写一个函数，要求输入一个数字，判断其是否为质数。(质数的定义为：一个大于 1 的数，除了 1 和其自身以外，不能被其他自然数整除)。

    ***Solution by Ouyang:***

    ```python
    num=int(input('请输入一个大于1的自然数:'))
    if num>1:
        for i in range(2,num):
            if num % i==0:
                print('是合数')
                break
            else:
                None
        else:
            print('是质数')
    else:
        print('输入值有误')
    ```
  



- ### 2022.4.30

    **题目描述**

    编写一个函数，用于判断输入的年份是否为闰年(闰年的定义：能被 4 整除但不能被 100 整除，或者能直接被 400 整除)

    ***Solution by Ouyang:***
    ```python
    try:
        year=int(input("请输入一个年份:"))
        if (year%4==0) and (year%100!=0) or (year%400)==0:
            print("{}年是闰年".format(year))
        else:
            print("{}年不是闰年".format(year))
    except:
        print("您输入有误!")
    ```


- ### 2022.5.01

    **题目描述**

    给定下列齐次方程组，判断是否存在非零解？如有，则求出所有解。
    $$
    \begin{cases}
    x_1 + x_2 + x_3 + 2x_4 + x_5 &= 0 \\
    3x_1 + 2x_2 + x_3 + 5x_4 + -3x_5 &= 0 \\
    x_2 + 2x_3 + x_4 + 6x_5&= 0 \\
    5x_1 + 4x_2 + 3x_3 + 9x_4 -x_5 &= 0 
    \end{cases}
    $$

    ***Solution by Ouyang:***

- ### 2022.5.02

    **题目描述**

    求解下列非齐次线性方程组
    $$
    \begin{cases}
    2x + y - z + w &= 1 \\
    4x + 2y - z + w &= 2 \\
    2x + y - z - w &= 1 
    \end{cases}
    $$

    ***Solution by Ouyang:***


- ### 2022.5.03

    **题目描述**

    当 $\lambda$ 取何值时，非齐次线性方程组$
    \begin{cases}
    2x + y - z + w &= 1 \\
    4x + 2y - z + w &= 2 \\
    2x + y - z - w &= 1 
    \end{cases}$ (1) 有唯一解 (2) 无解 (3) 有无穷多解

    ***Solution by Ouyang:***

- ### 2022.5.03

    **题目描述**

    设 $A $是 $m×n$ 矩阵，$Ax=b$ 有解，则  ( )
    (A) 当 $Ax = b$ 有唯一解时，$m = n$
    (B) 当 $Ax = b$ 有无穷多解时，$R(A) < m$
    (C) 当 $Ax = b$ 有唯一解时，$R(A) = n$
    (D) 当 $Ax = b$ 有唯一解时，$Ax = 0$ 只有非零解

    ***Solution by Ouyang:***

- #### 2022.5.04

    **题目描述**

    设 $A$ 是 $m×n$ 矩阵，如果 $m < n$，则  ( )
    (A) $Ax = b$ 必有无穷多解
    (B) $Ax = b$ 必有唯一解
    (C) $Ax = 0$ 必有非零解
    (D) $Ax = 0$ 必有唯一解

    ***Solution by Ouyang:***

- ### 2022.5.05

    **题目描述**

    设 $A$ 是 $m×n$ 矩阵，齐次线性方程组 $Ax = 0$ 仅有零解的充要条件是 $R(A)$ ( )
    (A) 小于 $m$  (B)   小于 $n$ (C) 等于 $m$ (D) 等于 $n$

    ***Solution by Ouyang:***


