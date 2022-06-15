### HW_1 Postman
#### [EP_1](#EP_1)
#### [EP_2](#EP_2)
#### [EP_3](#EP_3)
#### [EP_4](#EP_4)
#### [EP_5](#EP_5)
#### [EP_6](#EP_6)
#### [EP_7](#EP_7)


##### Создать запросы в Postman

Protocol: http  
IP: 162.55.220.72  
Port: 5005

*В Postman создать новую коллекцию HW_1_Postman. В коллекции добавить запрос(Add request)*

---
<a name="EP_1">EP_1</a>   
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
<a name="EP_2">EP_2</a>  
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
<a name="#EP_3">EP_3</a>  
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
<a name="EP_4">EP_4</a>  
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
<a name="EP_5">EP_5</a>  
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
<a name="EP_6">EP_6</a>  
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
<a name="EP_7">EP_7</a>  
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
