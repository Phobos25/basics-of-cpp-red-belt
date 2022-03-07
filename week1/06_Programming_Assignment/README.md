# Practice Programming Assignment: Макрос UNIQ_ID

Разработать макрос UNIQ_ID, который будет формировать идентификатор, уникальный в пределах данного cpp-файла. Например, следующий код должен компилироваться и работать:  

```cpp
int UNIQ_ID = 5;
string UNIQ_ID = "hello!";
```
В рамках данной задачи допускается, что код

```cpp
int UNIQ_ID = 5; string UNIQ_ID = "hello"; // оба определения на одной строке
```  

не будет компилироваться. Заготовка решения:

[uniq_id](uniq_id.cpp)

Подсказки:

* подумайте, как можно применить макрос __LINE__

* ознакомьтесь с конкатенацией в макросах, а также с макросами в качестве параметров других макросов по ссылкам ниже:

[Основы](https://www.iar.com/knowledge/learn/programming/basics-of-using-the-preprocessor)

[Самое интересное](https://www.iar.com/knowledge/learn/programming/advanced-preprocessor-tips-and-tricks)
