# Выпускная квалификационная работа: пограммный код

## Описание

Данный репозиторий посвящён програмному коду моей выпускной квалификационной работы. 

В состав репозитория входят 16 файлов с данными формата .xls, которые я скачал с сайта [Росстата](https://obdx.gks.ru/), 4 файла с данными формата .xlsx с сайта [АТС](https://www.atsenergo.ru/results/rsv), собраными вручную и объединённые с помощью другого програмного кода, 1 файл Jupyter Notebook и сам файл README.md.

## Содержание файла .ipynb

Данный файл имеет следующую структуру:

- Извлечение данных
- Очистка данных
- Анализ данных: агрегация (2005-2014)
- Анализ данных: визуализация (2005-2014)
- Анализ данных: агрегация (2015-2020)
- Анализ данных: визуализация (2015-2020)
- Анализ данных: таблицы относительных изменений
- Регрессионная модель в рамках рынка электроэнергии

Все разделы кроме последнего опираются на данные с сайта Росстата, кроме последнего, который был разработан при помощи данных, собранных с сайта АТС (ссылки есть в [описании]([## Описание](https://github.com/Alex-Zaberlin/final_qualifying_work/blob/main/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5))). Графики были построены с помощью библиотеки `plotly`, поэтому не отображаются корректно на GitHub, однако на локальной машине должны работать. Пути, необходимо будет изменить под директорию, в которой будут находиться скачанные данные.
