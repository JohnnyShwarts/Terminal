# Terminal


## ***Задание №1 - (__GitBash__) commands***

1. + Посмотреть где я  ```pwd```
2. + Создать папку  - ```mkdir bashTest```
3. + Зайти в папку  - ```cd bashTest/```
4. + Создать 3 папки - ```mkdir 1_p 2_p 3_p```
5. + Зайти в любоую папку - ```cd 1_p/```
6. + Создать 5 файлов - ```touch 1.txt 2.js 3.html 4.json 5.json```
7. + Создать 3 папки - ```mkdir one_folder two_folder three_folder```
8. + Вывести список ```содержимого папки - ls -la```
9. + Открыть любой txt файл - ```nano 1.txt```
10. + написать туда что-нибудь, любой текст

```
Вот солнца свет, уходит из окошка,
Зима на улице, зима берет своё.
И лектор говорит...
-Ребят, еще немножко
-Закончу лишь рассказ, про это полотно…
Смотрите вот, какие краски, какие яркие цвета,
"Яка" глубокая картина и как красива же она!
В аудитории затишье, тишина...
А время, без пяти минут четыре
Открытое окно, а там зима - она!
Все тише, тише - пушистый снег ложится на дома...
```
[![Ла-Эль-Джонс- "Зима"](https://stihi.ru/pics/2007/11/26/3304.jpg?5093)](https://stihi.ru/2007/11/26/3304)

[Ла-Эль-Джонс](https://stihi.ru/avtor/habano)

11. + __сохранить и выйти__ - ```ctrl+x ->save (y/n)```

![stihi_1](https://user-images.githubusercontent.com/104720406/174435338-b48baade-02ef-4879-ba49-af956d7aab78.png)
____

12. __Выйти из папки на уровень выше__ - ```cd ..```

![1_12_1](https://user-images.githubusercontent.com/104720406/174435230-c3c1fe11-4ee5-454c-adba-2528625ead4a.png)

![1_12](https://user-images.githubusercontent.com/104720406/174435244-ad9739ec-076b-4c8a-b1e8-a4b32c7e3463.png)
____

13. __Переместить любые 2 файла, которые вы создали, в любую другую папку__ -  ```mv C:/Users/Екатерина/Desktop/bashTest/1_p/4.json C:/Users/Екатерина/Desktop/bashTest/1_p/5.json C:/Users/Екатерина/Desktop/bashTest/1_p/one_folder```

![1_mv](https://user-images.githubusercontent.com/104720406/174435284-37bdee5a-e900-42e0-96eb-b5260f57b418.png)

____
14. __Cкопировать любые 2 файла, которые вы создали, в любую другую папку__ - ```cp C:/Users/Екатерина/Desktop/bashTest/1_p/one_folder/4.json C:/Users/Екатерина/Desktop/bashTest/1_p/one_folder/5.json C:/Users/Екатерина/Desktop/bashTest/1_p/three_folder```

![cp_1](https://user-images.githubusercontent.com/104720406/174435288-8e109078-945c-4ec9-b768-23a0955133e6.png)

____
15. __Найти файл по имени__ - ```find . -name 3.html```

![find_3ht](https://user-images.githubusercontent.com/104720406/174435290-9ee464df-bbde-4205-bc06-2e2e7ebaea6d.png)


16. __Просмотреть содержимое в реальном времени (команда grep) изучите как она работает__ - ```grep 'зима' C:/Users/Екатерина/Desktop/bashTest/1_p/1.txt```

![grep_зима](https://user-images.githubusercontent.com/104720406/174435297-a1712100-6f70-45ae-9557-343a763c534e.png)

____
17. __Вывести несколько первых строк из текстового файла__ - ```head -2 C:/Users/Екатерина/Desktop/bashTest/1_p/1.txt```

18. __Вывести несколько последних строк из текстового файла__ - ```tail -4 C:/Users/Екатерина/Desktop/bashTest/1_p/1.txt```

![head_tail](https://user-images.githubusercontent.com/104720406/174435313-09eaa917-9807-4216-b221-af232382d299.png)
____

19. __Просмотреть содержимое длинного файла (команда less) изучите как она работает__ - ```less C:/Users/Екатерина/Desktop/bashTest/1_p/1.txt```

![less](https://user-images.githubusercontent.com/104720406/174435320-1c2d1755-9710-4806-886c-4b3b2750b53b.png)
____
21. __Вывести дату и время__ - ```date```

![date](https://user-images.githubusercontent.com/104720406/174435342-9732a9b4-7976-4ed4-b356-ee919b7a7c67.png)
____

## ****Задание №2 - Отправить http запрос на сервер.***

```curl 'http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000'```

```json
  "age": "32",
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
    "u_salary_1_5_year": 4000
  },
  "name": "Vadim",
  "salary": 1000
}

```

## ****Задание №3 - Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13***

```
Файл - HW.sh
Комманда - ./HW.sh

```

```js
 #!/bin/bash
  cd 2_p
  mkdir 1_pp 2_pp 3_pp
  cd 1_pp/
  touch 1.txt 2.txt 3.txt 4.json 5.json
  mkdir 1_1 2_2 3_3
  ls -la
  mv C:/Users/Екатерина/Desktop/bashTest/2_p/1_pp/1.txt C:/Users/Екатерина/Desktop/bashTest/2_p/1_pp/2.txt C:/Users/Екатерина/Desktop/bashTest/2_p/1_pp/3_3
  
  ```
  ![script](https://user-images.githubusercontent.com/104720406/174449034-07d66358-c184-4f93-8918-e3ae82c6dfcf.png)


