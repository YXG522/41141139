# 41141139
## 解題說明
依據題目所提供的抽象資料型別與資料結構，實作一個polynomial類別

◎執行多項式加法

◎對給定的數值進行帶入運算

## 程式實作

[C++](HW2實作)

class Term {
    
    friend class Polynomial;

private:
    
    float coef;   // 係數
   
    int exp;      // 指數

};
