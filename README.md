# Recommandation system of films :movie_camera:

| Название файла/директории | Содержание файла |
|----:|:----------|
| notebook_v1.ipynb | Ноутбук формата .ipynb с детальным описанием проекта|

## Общие сведения
Этот проект представляет собой экспериментальную реализацию рекомендательной системы фильмов на основе content-based подхода и исключительно текстовых признаков. 

Для работы были взяты 3 датасета: movies_metadata.csv, ratings.csv, credits.csv с kaggle: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset. 

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

Процесс работы детально описан в ноутбуке, дополнительную информацию можно найти в нашем Notion'е:
reu-ds-club.notion.site/e8a1766982864282991170105011f111

Данные в коде подтягиваются из облачного хранилища, поэтому для начала работы достаточно просто запустить файл .ipynb в Jupyter Notebook или Google Collab.

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
| **ФИ** | **Role** | **Telegram**|
|----:|:----------:|:----|
| Валерия Авакян | Idea | @blacklerie |
| Исаева Диана| Text Data Processing | @iis_diink |
| Артем Мичурин | Main Pipeline Creation | @devyat999999999 |
| Петр Сокерин | Team Lead | @Petr_Sokerin |
