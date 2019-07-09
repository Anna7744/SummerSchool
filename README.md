# SummerSchool

## Mermaid 8.0 Project Refactoring
Documentation refactoring is the process of restructuring existing docomentation without changing its external behavior.
- Refactoring is intended to improve nonfunctional attributes of the software. 
- Advantages include improved code readability and reduced complexity; *these can improve source-code maintainability and create a more expressive internal architecture or object model to improve extensibility.*

| Benefits of project  | Techniques | 
| ------------- | ------------- |
| Improvement of docs  | Read and improve  |
| Improvement of docs | Testing by the other techwriters  |
    
    
![](http://www.52dazhew.com/data/out/62/585899957-cute-pig-wallpapers-for-ipad.jpg)

![](file:///Users/a.malukhina/Pictures/99px_ru_wallpaper_457_mini_svinka_the_pig_artlist_collection.jpg)

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

## СПРАВОЧНИК API

Метод АРI позволяет получить список продуктов по ID проекта и статусы подключения. 

## HTTP-ЗАПРОС
    

    GET https://api.example.com/products/{project_id} 
    Headers:
Authorization: Basic <your_authorization_basic_key>

### ПАРАМЕТРЫ ЗАПРОСА
**project_id**

    _integer_
    
ID проекта

## HTTP-ОТВЕТ
    
    {
          Product1:connected,
          Product2:disconnected
     }

### ПАРАМЕТРЫ ОТВЕТА

**Product**

    _string_

ID продукта
