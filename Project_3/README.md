# Проект 3. EDA + Feature Engineering. Соревнование на Kaggle

## Оглавление
[1. Описание проекта](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Описание-проекта)

[2. Какой кейс решаем](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Какой-кейс-решаем)

[3. Краткая информация о данных](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Этапы-работы-над-проектом)

[5. Результаты](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Результаты)

[6. Выводы](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Выводы)

## Описание проекта

Одна из проблем компании Booking - нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведет себя нечестно, и его стоит проверить.

:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

## Какой кейс решаем

Проект состоит из следующих этапов:
- знакомство с данными;
- анализ и исследование данных;
- проектирование признаков;
- отбор признаков;
- создание и обучение модели;
- получение результатов.

:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

## Краткая информация о данных

Датасет содержит следующие признаки:
- *hotel_address* — адрес отеля;
- *review_date* — дата, когда рецензент разместил соответствующий отзыв;
- *average_score* — средний балл отеля, рассчитанный на основе последнего комментария за последний год;
- *hotel_name* — название отеля;
- *reviewer_nationality* — страна рецензента;
- *negative_review* — отрицательный отзыв, который рецензент дал отелю;
- *review_total_negative_word_counts* — общее количество слов в отрицательном отзыв;
- *positive_review* — положительный отзыв, который рецензент дал отелю;
- *review_total_positive_word_counts* — общее количество слов в положительном отзыве;
- *reviewer_score* — оценка, которую рецензент поставил отелю на основе своего опыта;
- *total_number_of_reviews_reviewer_has_given* — количество отзывов, которые рецензенты дали в прошлом;
- *total_number_of_reviews* — общее количество действительных отзывов об отеле;
- *tags* — теги, которые рецензент дал отелю;
- *days_since_review* — количество дней между датой проверки и датой очистки;
- *additional_number_of_scoring* — есть также некоторые гости, которые просто поставили оценку сервису, но не оставили отзыв. Это число указывает, сколько там действительных оценок без проверки.
- *lat* — географическая широта отеля;
- *lng* — географическая долгота отеля.

:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

## Этапы работы над проектом

- На первом этапе проведен познакомимся с данными, посмотрим, что они из себя представляют, рассмотрим основную информацию о датасете;
- На втором этапе проведем анализ данных, расмотрим каждый признак получше;
- На третьем этапе займемся проектированием признаков, использую информацию, имеющуюся в датасете, а также, по возможности, стороннюю;
- Четвертый этап посвятим отбору признаков;
- На пятом этапе создадим и обучим модель на тренировочных данных;
- На заключительном шестом этапе посмотрим, какой показатель покажет модель, и сделаем вывод по результату.


:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

## Результаты

Результат предсказания модели по показателю МАЕ равен 13.0825. Целевой показатель по заданию курса - МАЕ менее 13,5.

:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

## Выводы

Было много поптыток создания значащих признаков из имеющихся данных, а также подгрузки дополнительных, но показатель МАЕ особо не менялся. Не помогла стандартизация и нормализация. Дело сдвинулось с места, когда начал разбирать текс отзывов и пытаться выделять из него слова, которые могли бы отразить тональность отзыва - положительны или отрицательный, ругают отель или хвалят. Вручную это очень тяжело, так как отзывов огромное количество и все посмотреть нереально. Попытался сделать это без дополнительных библиотек.

P.S. На проект ушло больше года, учитывая все перерывы, потому что выгорел, пропал интерес от перенасыщения. Как-то начал курс бодро, активно, но запала хватило не надолго. Оказалось, на длинной дистанции тяжело сохранять такой темп, особенно когда основная работа требует того же, что и изучение нового материала по курсу - внимательности, концентрации, усидчивости (работаю инженером-конструктором). За день этот ресурс исчерпывается и на курс мало что остается. В общем, собрался и продолжаю, что считаю маленькой победой - не сдался. Надеюсь, что далее получится распределяться силы более рационально. Спасибо за внимание.

:arrow_up:[к оглавлению](https://github.com/an-petruhin/My_Projects/tree/master/Project_3#Оглавление)

:arrow_up:[назад к проектам](https://github.com/an-petruhin/My_projects#Проекты)