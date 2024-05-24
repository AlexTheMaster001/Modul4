# Modul4
https://github.com/ItsLiventsev/NetSys_Demo_2024/blob/main/README.md

- ссылка на гайд Ливенцева


# Обоснование выбора OSPF и EIGRP
При настройке нет OSPF нет возможности корректно настроить соеденения по причине отсутсвия работы некоторых IP адреосв, в следсвие чего было принято решение использовать EIGRP.

# 1 задание.
Для начала, нужно зайти в настройки

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/0f1fd382-6ccc-4e11-9a56-1c9150daa561)

Далее, нужно поставить IPv4 Method, DNS и Routes в автоматический режим

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/7d9b0d40-7b1e-475d-b3d0-359e1cd4add4)

На этои этапе, настройка dhcp закончнена.

# 2 задание.
Заходим в терминал. Обзор - все приложения - терминал

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/21ea7a32-8f44-4558-8ba1-40efe28aedf2)

Далее, пишим su, чтобы войти под суперпользователем (root) и вводим пароль

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/0c5adf56-da62-4162-a4ac-d6e62d777b16)

Теперь нам нужно запретить заход на домены github.com и vk.com.
Открываем следующий файл (команда nano):

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/bc03f8c1-ce3d-4482-a053-9ea322e8e7d1)

И здесь вписываем дополнительные строчки

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/a4bd4841-c93d-4e6e-9da5-5d1a8e711bd9)

Сохраняем с помощью ctrl+x
Далее, проверяем, что нет доступа к этим доменам. Для этого, заходим в браузер и пробуем войти на эти сайты, у нас должна появится ошибка соеденения, значит все выполнено верно.

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/b7cd1ad8-4386-4c85-815a-2ff5ce08a3d4)


# 3 задание.
Заходим в настройки - пользователи - разблокировать

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/0b84c8b5-6c54-4e2f-a959-641769341603)

Далее, создаем нового пользователя с именем user и ставим ему пароль

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/837c8a74-b8e5-495a-8417-f8ce81be2daf)

Далее, выходим из сессии. Должен появится новый созданный пользователь user

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/c6427e62-8c0b-436d-b87e-896bce4fbc87)

# 4 задание.
Подключаем любой iso-образв DVD-привод. И проверяем, что он подключился

![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/6d9c3e10-a931-4630-97d3-9f9015b914dc)

Если вдруг не работает, нужно проверить в ESXI, подключен ли он

![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/b0c0ec70-9164-4c9c-aae0-54d7cd91c3e8)



![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/deec34ad-83d8-4d23-93f9-e8ff5bf26c01)

![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/7b8ecb43-5fee-484e-b498-d9e93f5aa6c3)

После этого, монтируем наш ISO-образ

![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/53d44c6c-47b6-41b2-be5d-7e8796acd998)

Проверяем, что образ успешно смонтирован

![image](https://github.com/AlexTheMaster001/Modul4_Demo/assets/161127648/9669c27c-ea9d-4e6a-893d-45269a95e374)

# 5 задание.
Для начала, проверям, что у нашего пользователя нет прав.

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/dcc8ccbe-59ca-4621-9c20-1e7464257509)

Теперь выдаем права

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/9ff20bfb-4bcb-45c2-907a-3a1226ef5850)

После этого, смотрим что права применились

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/d37be3ff-038b-439b-a310-52eeb1c90916)

# 6 задание.
Теперь создаем баннер с определенной информацией.
Для начала создаем сам файл.

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/7ce133de-2f7d-4204-b47f-2906f97f5177)

Внутри него прописываем следующую информацию

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/50d3b5ab-7eb9-4ab2-8a59-cb784ec2c4cd)

Сохраняем с помощью ctrl+x
Переходим к домашнему каталогу

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/ee521122-cb11-448e-80a5-fe6ff122127b)

Выдаем права на открытие файла

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/b774aef9-3b83-4175-a147-8096d54207fb)


Затем, запускаем этот скрипт

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/3e7ca6a1-39bc-4048-b00c-6273f64ad390)

У нас должна появится следующая инфа

![image](https://github.com/AlexTheMaster001/Modul4/assets/161127648/002b60d0-0824-41e5-9ac1-9ec7a00873b5)

