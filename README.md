# <center> Skillfactory Проект 3: Разведовательный анализ данных 

## Оглавление  
[1. Описание проекта](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Результат)    
[6. Выводы](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Выводы) 

### Описание проекта    
Представьте, что вы работаете дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

Вам поставлена задача создать такую модель. 

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Целью данного проекта является очистка данных, проектирование новых признаков, и полная подготовка данных для последующего обучения модели.

**Что практикуем**     
    -Решать Data-Science кейсы
    -закреплять пройденный в курсе материал
    -Python
    -EDA


### Краткая информация о данных
#### Связанные с отелем признаки
1. hotel_name - full hotel name;
2. hotel_address - address: street, post code, city, country;
3. lat - hotel latitude coordinate;
4. lng - hotel longitude coordinate;
5. average_score - average hotel rating;
6. total_number_of_reviews - total number of hotel reviews;
7. additional_number_of_scoring - number of hotel scores without review.

#### Связанные с рецензентом признаки
1. reviewer_nationality - reviewer nationality;
2. total_number_of_reviews_reviewer_has_given - total number of reviews reviewer has given;
3. tags - tags describing stay in the hotel.

#### Связанные с отзывом признаки 
1. review_date date of review;
2. days_since_review difference in the number of days between review date and scrape date;
3. negative_review text of negative review;
4. review_total_negative_word_counts negative review words number;
5. positive_review text of positive review;
6. review_total_positive_word_counts positive review words number.


:arrow_up:[к оглавлению](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Оглавление)


### Этапы работы над проектом  
Проект разделен на пять этапов:
    1. Загрузка данных и предварительный анализ
    2. EDA
        2.1 Общий анализ
        2.2 Поиск взаимосвязей (в ноутбуке отсутствует)
        2.3 Создание и преобразование признаков
            2.3.1 Извлечение информации из текстовых признаков
            2.3.2 Работа с датами
            2.3.3 Обработка пропусков
        2.4 Вклад признаков в Формирование целевого признака
        2.5 Анализ мультиколлинеарности и отбор признаков
    3. Обучение модели
    4. Сабмит)

Все эти этапы проработаны сначала на локальной машине, а после загружены на Kaggle.

:arrow_up:[к оглавлению](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Оглавление)


### Результаты:  
Пришлось повозиться с данным проектом, сил на него потратил не мало. Главной сложностью было, как не странно, отсутствие каких либо рамок. Не было никаких предписаний, о том что делать, как делать и тд. Проект наделен индивидуальным подходом к решению задачи, которая состояла в получении лучшего значения MAPE (mean-absolute-percentage-error). Мне удалось добиться MAPE = 12.115, что вполне себе неплохой результат, хоть есть и место для роста. 
В заключение хотелось бы сказать, что во время проекта, путем множества ошибок, я обрел не мало знаний, и в целом решением своим удовлетворен. 

:arrow_up:[к оглавлению](https://github.com/KarpovGm/Booking_review_Project_3/blob/main/README.md#Оглавление)
