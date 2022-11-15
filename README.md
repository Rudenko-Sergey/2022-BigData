# 2022-BigData
Рабочий репозиторий курса "Большие данные"


Презентация по курсу (обновляемая): https://docs.google.com/presentation/d/1xZ51nq1IWvccSrLzHo_QyaDQPvMBiWeUhoyPND-ARzo/edit?usp=sharing

Для работы необходим python 3.9 и выше.
Библиотеки: numpy, pandas, matplotlib, tensorflow
Редактор любой. Из неплохих: IDLE (родной, идёт вместе с установщиком), Visual Studio Code, notepad++, PyCharm, vim (для любителей сначала страдать, потом наслаждаться)

Работа с блокнотами онлайн, с возможностью подключения удалённых мощностей гугла (GPU, TPU): https://colab.research.google.com/

Таблица, где я буду отмечать сданные работы: 

Сервер в Дискорд, где буду дублировать: https://discord.gg/MzPkCYf4Dh
Мой контакт: nsmorozov@rf.unn.ru

В своей папке можете делать все что угодно, в чужие не залезать, в корневую тоже. Я буду ориентироваться на файлы, где в названии будет номер лабораторной.


# [1] Симуляция HDFS

Дописать имплементации методов:

- разбиение пространства хостов на блоки;

- проверка количества репликаций и дозаписывание недостающих копий;

- обработку запроса "complete" от клиенгта;

- список блоков на каждой DataNode;

- методы DataNode для записи блоков: обновления статуса в списке, ответ на запрос "какие блоки хранишь" от NameNode (его тоже написать).

# [2] Простые случаи Map-Reduce

Для нескольких файлов с оценками какао посчитать количество суммарных упоминаний каждой из стран.

# [3] Сбор данных с сайта

Для https://royallib.com/ собрать информацию (название и год издания) о книгах жанра:

1. Любовные романы

2. Религия и духовность

3. Справочная литература

4. Детское

5. Наука, Образование

Свой вариант определяется как len('Фамилия Имя Отчество') * (номер дня рождения, считая 27 ноября 1997 днем номер 0) % 5 + 1
