# 6.1_Medvedeva_homework

В репозитории представлено:
1. Коллекция запросов в Postman для проверки позитивных и негативных сценариев создания тасок в приложении sqlverifier;
2. Environment для коллекции;
3. CSV файл с тестовыми данными для коллекции запросов.

Для того, чтобы использовать приложенные данные, воспользуйтесь инструкцией.

## Необходимые условия для работы:
1. Приложение Postman. Если у вас не установлен Postman, воспользуйтесь [ссылкой для скачивания приложения для своей операционной системы](https://www.postman.com/downloads/). И аккаунт в приложении. 
2. Аккаунт на [GitHub](https://github.com/)
3. Вам необходимо интегрировать приложение Postman со своим аккаунтом на GitHub. [Инструкция](https://learning.postman.com/docs/integrations/available-integrations/github/)

## Инструкция по скачиванию и взаимодействию к коллекцией, окружением и приложенными данными
1. В левой боковой панели выберите APIs
2. Выше нажмите кнопку "Import"
3. В открывшемся модальном окне нажмите кнопку "Other Sourses" и выберите из выпадающего меню GitHub
4. В поле  Organization введите fiolentanna
5. В поле Repository введите 6.1_Medvedeva или выберите его из доступных
6. В поле Branch выберите main
7. Нажмите кнопку "Continue"
8. В открытом окне представлены выбранными коллекция и окружение. Оставьте и выбранными и нажмите кнопку "Import"
   
Коллекция и окружения загружены в Postman

9. Выберите APIs
10. У New API  нажмите на три точки правее (...) и выберите Add collection, затем выберите Copy existing collection.
11. В открывшемся модальном окне выберите скаченную коллекцию и нажмите кнопку Сopy Collection -> Коллекция скопирована
12. Пройдите по [ссылке](https://github.com/fiolentanna/6.1_Medvedeva/blob/main/5.2_Medvedeva_test_data.csv)  и скачайте файл с тестовыми данными в формате CSV

## Запуск коллекции с использованием тестовых данных
1. Кликните по коллекции в меню Postman
2. Выше справа нажмите кнопку "Run"
3. В крайнем правом окне кликните кнопку Select File  под надписью Data и выберите скаченный файл в формате CSV, в нем представлены тестовые данные для happy_path_tests  и sad_path_test
4. В Run results можно ознакомиться c результатами тестирования
   


