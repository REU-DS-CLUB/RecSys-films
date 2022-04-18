# Recommandation system of films :movie_camera:

| Название файла/директории | Содержание файла |
|----:|:----------|
| notebook_v1.ipynb | Ноутбук формата .ipynb  с полным описанием проекта и выводами|

## Описание
Рекомендательная система по фильмам.
Данные взяты с kaggle: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset. 
Текстовые данные представлены на английском языке.
Использовались 3 датасета: movies_metadata.csv, ratings.csv, credits.csv.
Из датасета movies_metadata.csv использовались столбцы:
* id - id фильмов
* title - название фильмов
* overview - описание фильмов
* genres - жанры фильмов
* production_companies - выпускающая компания

Из датасета credits.csv:
* crew - столбец, откуда вытаскивается ФИО режиссера

Из датасета ratings.csv:
* rating - рейтинги фильмов

Изучение работы текстовых content-based рекомендательных систем и создание алгоритма, который предсказывает актуальные пользователю фильмы на основе их описания и его предпочтений.
Входные текстовые данные требуют предобработки, а именно:
- Приведение текста к нижнему регистру;
- Удаление пунктуации;
- Удаление стоп-слов;
- Разбиение текста на токены;
- Нормализация текстовых данных.

Запуск файлов .ipynb осуществляется в Jupyter Notebook или Google Collab.

## Документация

* [Документация по работе с Python](https://www.python.org/)
* [Документация по работе с gdown](https://pypi.org/project/gdown/)
* [Документация по работе с pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
* [Документация по работе с numpy](https://numpy.org/doc/)
* [Документация по работе с random](https://docs.python.org/3/library/random.html)
* [Документация по работе с srting](https://docs.python.org/3/library/string.html)
* [Документация по работе с sklearn](https://scikit-learn.org/stable/)
* [Документация по работе с scipy](https://docs.scipy.org/doc/)
* [Документация по работе с heapq](https://docs.python.org/3/library/heapq.html)
* [Документация по работе с ast](https://docs.python.org/3/library/ast.html)
* [Документация по работе с re](https://docs.python.org/3/library/re.html)
* [Документация по работе с tgdm](https://pypi.org/project/tqdm/)
* [Документация по работе с pymorphy2](https://pymorphy2.readthedocs.io/en/0.2/user/index.html)
* [Документация по работе с keras](https://ru-keras.com/home/)
* [Документация по работе с nltk](https://www.nltk.org/)
* [Документация по работе с gensim](https://radimrehurek.com/gensim/auto_examples/index.html)

## :telephone_receiver: Контакты
| **ФИ** | **Tелефон** | **Telegram**|
|----:|:----------:|:----|
| Валерия Авакян |  | @blacklerie |
| Исаева Диана| +7(964)0497904| @iis_diink |
| Артем Мичурин | +7(916)3176642 | @devyat999999999 |
| Петр Сокерин | +7(977)8813402 | @Petr_Sokerin |