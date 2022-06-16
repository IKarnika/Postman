## HW Postman

### [HW_1](#HW)

#### [EP_1](#1)
#### [EP_2](#2)
#### [EP_3](#3)
#### [EP_4](#4)
#### [EP_5](#5)
#### [EP_6](#6)
#### [EP_7](#7)

### [HW_2](#HW2)  
#### [EP http://162.55.220.72:5005/first  ](#first)  
#### [EP http://162.55.220.72:5005/user_info_3](#user_info_3)  

<a name="HW"></a>
#### HW_1 Создать запросы в Postman

Protocol: http  
IP: 162.55.220.72  
Port: 5005

*В Postman создать новую коллекцию HW_1_Postman. В коллекции добавить запрос(Add request)*

---
<a name="1"></a>   
##### EP_1  
Method: GET  
EndPoint: /get_method  
Request url params:  
name: str   
age: int   

*В url прописать http://162.55.220.72:5005/get_method
В Params добавить ключи и значения:*
Key| Value  
:--:|:--:  
name | Helen  
age | 23  

*Сохранить(Save) и отправить(Send)*
 
response:  

```json
[ 
  "Helen",  
  "23"  
]
```

---
<a name="2"></a>  
##### EP_2  
Method: POST  
EndPoint: /user_info_3  
Request form data:  
name: str  
age: int  
salary: int

*В url прописать http://162.55.220.72:5005/user_info_3 Выбрать тип запроса POST, на вкладке Body выбрать Form-data, добавить ключи и зачения:*
Key| Value  
:--: | :--:  
name | Nata  
age | 18  
salary | 2000

*Сохранить(Save) и отправить(Send)*  

response:  

```json
{
    "age": "18",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "u_salary_1_5_year": 8000
    },
    "name": "Nata",
    "salary": 2000
}
```

---
<a name="3"></a>  
##### EP_3  
Method: GET  
EndPoint: /object_info_1  
Request url params:  
name: str  
age: int   
weight: int  

*В url прописать http://162.55.220.72:5005/object_info_1 Выбрать тип запроса GET, добавить ключи и зачения в Params:*
Key| Value  
:--: | :--:  
name | Alex  
age | 28  
weight | 67

*Сохранить(Save) и отправить(Send)*  

response:  

```json
{
    "age": 28,
    "daily_food": 0.804,
    "daily_sleep": 167.5,
    "name": "Alex"
}
```
---
<a name="4"></a>  
##### EP_4  
Method: GET  
EndPoint: /object_info_2  
Request url params:  
name: str  
age: int   
salary: int  

*В url прописать http://162.55.220.72:5005/object_info_2 Добавить ключи и зачения в Params:*
Key| Value  
:--: | :--:  
name | Chak  
age | 67  
salary | 3200  

*Сохранить(Save) и отправить(Send)*  

response: 

```json
{
    "person": {
        "u_age": 67,
        "u_name": [
            "Chak",
            3200,
            67
        ],
        "u_salary_5_years": 13440.0
    },
    "qa_salary_after_1.5_year": 10560.0,
    "qa_salary_after_12_months": 8640.0,
    "qa_salary_after_3.5_years": 12160.0,
    "qa_salary_after_6_months": 6400,
    "start_qa_salary": 3200
}
```
---
<a name="5"></a>  
##### EP_5  
Method: GET  
EndPoint: /object_info_3  
Request url params:  
name: str  
age: int   
salary: int  

*В url прописать http://162.55.220.72:5005/object_info_3 Добавить ключи и зачения в Params:*
Key| Value  
:--: | :--:  
name | Liza  
age | 27  
salary | 1800  

*Сохранить(Save) и отправить(Send)*  

response: 

```json
{
    "age": "27",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 7200
    },
    "name": "Liza",
    "salary": 1800
}
```
---
<a name="6"></a>  
##### EP_6  
Method: GET  
EndPoint: /object_info_4  
Request url params:  
name: str  
age: int   
salary: int  

*В url прописать http://162.55.220.72:5005/object_info_4 Добавить ключи и зачения в Params:*
Key| Value  
:--: | :--:  
name | Kate  
age | 44  
salary | 3400  

*Сохранить(Save) и отправить(Send)*  

response: 

```json
{
    "age": 44,
    "name": "Kate",
    "salary": [
        3400,
        "6800",
        "10200"
    ]
}
```
---
<a name="7"></a>  
##### EP_7  
Method: POST  
EndPoint: /user_info_2  
Request form data:  
name: str  
age: int   
salary: int  

*В url прописать http://162.55.220.72:5005/object_info_2 Выбрать метод запроса POST, на вкладке Body выбрать form-data, добавить ключи и зачения:*
Key| Value  
:--: | :--:  
name | Goose  
age | 2  
salary | 100  

*Сохранить(Save) и отправить(Send)*  

response: 

```json
{
    "person": {
        "u_age": 2,
        "u_name": [
            "Goose",
            100,
            2
        ],
        "u_salary_5_years": 420.0
    },
    "qa_salary_after_1.5_year": 330.0,
    "qa_salary_after_12_months": 270.0,
    "qa_salary_after_3.5_years": 380.0,
    "qa_salary_after_6_months": 200,
    "start_qa_salary": 100
}
```


<a name="HW2"></a>
#### HW_2  

<a name="first"></a>
##### EP http://162.55.220.72:5005/first  
1. Отправить запрос  
*Создать новую колеекцию HW_2.  
Добавить запрос(add request) Req_1  
Вести url http://162.55.220.72:5005/first  
Сохранить (Save) и отправить (Send)* 

2. Статус код 200  
*Переключиться на вкладку Tests, в сниппетах(Snippets) выбрать Status code: Code is 200*  
```
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});  
```  

*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174010311-3ab8fb14-f18d-4ff4-ac28-032f3d16df59.png)  

3. Проверить, что в body приходит правильный string  

![](https://user-images.githubusercontent.com/103427482/173826225-8c0e00f1-c1b3-4508-a767-7110655df5a3.png)  

*В сниппетах(Snippets) выбрать Response body: is equal to a string  
Вписать значение строки*  
```  
pm.test("Body is correct", function () {
    pm.response.to.have.body("This is the first responce from server!");
});  
```
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174012202-c601c29d-7607-49a7-b457-9f6b20e25671.png)  

<a name="user_info_3"></a>
##### EP http://162.55.220.72:5005/user_info_3  
1. Отправить запрос  
*Дублировать предыдущий запрос, переименовать в Req_2  
Ввести url http://162.55.220.72:5005/user_info_3  
Метод - POST  
Вкладка Body, form-data  
Ввести ключи и значения:*  

Key| Value  
:--: | :--:  
name | Vishenka  
age | 18  
salary | 2000  

*Сохранить (Save) и отправить (Send)*  

2. Статус код 200  
*Переключиться на вкладку Tests, в сниппетах(Snippets) выбрать Status code: Code is 200*  
```
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});  
```  

*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174010311-3ab8fb14-f18d-4ff4-ac28-032f3d16df59.png)  

3. Спарсить response body в json  
*На вкладке Tests прописать*  
```  
let responseData = pm.response.json();
console.log(responseData);  
```  
4. Проверить, что name в ответе равно name s request (name вбить руками)  
*В сниппетах выбрать Response body: JSON value check  
Внести необходимые изменения*
```   
pm.test("name s request", function () {
    let jsonData = pm.response.json();
    pm.expect(jsonData.name).to.eql("Vishenka");
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174016697-403fec2a-e10f-4c38-877c-1d3ed71332c1.png)  

5. Проверить, что age в ответе равно age s request (age вбить руками)  
*Дублировать предыдущий скрипт  
Внести необходимые изменения*  
```  
pm.test("age s request", function () {
    let jsonData = pm.response.json();
    pm.expect(jsonData.age).to.eql("18");
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174017713-434a462d-5619-472c-818c-16325b587446.png)  

6.Проверить, что salary в ответе равно salary s request (salary вбить руками)  
*Дублировать предыдущий скрипт  
Внести необходимые изменения*  
```  
pm.test("salary s request", function () {
    let jsonData = pm.response.json();
    pm.expect(jsonData.salary).to.eql(2000);
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174018120-a13cc939-4ba2-4915-9112-e1ce75adc83f.png)  

7. Спарсить request
*На вкладке Tests прописать*  
```  
let requestData = request.data;
console.log(requestData);  
```  
8. Проверить, что name в ответе равно name s request (name забрать из request)  
*В сниппетах выбрать Response body: JSON value check  
Внести необходимые изменения*  
```  
pm.test("name request", function () {
    pm.expect(responseData.name).to.eql("Vishenka");
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174021208-6feb7fb5-a2fb-47ee-b3bb-8af0f601d35d.png)  

9. Проверить, что age в ответе равно age s request (age забрать из request)  
*Дублировать предыдущий скрипт  
Внести необходимые изменения*  
```  
pm.test("age request", function () {
    pm.expect(responseData.age).to.eql("18");
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174021968-6548568e-8e26-47a8-b67f-b254efb3ccc5.png)  

10. Проверить, что salary в ответе равно salary s request (salary забрать из request)  
*Дублировать предыдущий скрипт  
Внести необходимые изменения*  
```  
pm.test("salary request", function () {
    pm.expect(responseData.salary).to.eql(2000);
});  
```  
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174022262-d0ec1435-7901-45d3-a93f-77904a2ee731.png)  

11. Вывести в консоль параметр family из response  
```  
console.log(responseData.family);  
```  
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)  
```  
let salary_check = responseData.salary * 4;
let salary1_5 = responseData.family.u_salary_1_5_year;

pm.test("salary*4 check", function () {
    pm.expect(salary_check).to.eql(salary1_5);
});  
```   
*Сохранить (Save) и отправить (Send)  
На вкладке Test Results посмотреть результат*  
![](https://user-images.githubusercontent.com/103427482/174026929-5b9ee0e6-d9ba-4bf0-8a3b-f017675b66f5.png)  
