# 41141139
## 解題說明
依據題目所提供的抽象資料型別與資料結構，實作一個polynomial類別

◎執行多項式加法

◎對給定的數值進行帶入運算

## 程式實作

[C++](HW2實作)

**class Term（私有內部類別）**

class Term {
    
    friend class Polynomial;

private:
    
    float coef;   // 係數
   
    int exp;      // 指數

};

**class Polynomial:**

Term* termArray: 儲存所有非零項的動態陣列

int capacity: 陣列的容量

int terms: 當前項數

**公開功能函式：**

Add(const Polynomial&): 加法

Mult(const Polynomial&): 乘法

Eval(float): 求值

NewTerm(float, int): 新增一項

運算子多載：>>, <<
