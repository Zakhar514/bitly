# Считаем клики по ссылкам

Эта программа создана для того, чтобы облегчить получение bitly ссылок и подсчёта кликов по ним. 

### Установка

После того как вы скачали все файлы нужно установить библиотеки.
Все зависимости кода и их версии которые записаны в файл `requirements.txt`

## Как пользоваться 

В первую очеред вам нужен `BITLINK TOKEN`, после того как вы его получите, вставляете его в `env` файл.

Запускать код нужно только из командной строки! Если пытаться запустить код через кнопку, то программа не запуститься и выведет ошибку 

После запуска программы вставляйте в командную строку любую ссылку или битли.

(Если вы вставляете битли ссылку, то программа будет считать вам количество ссылок по ней,
а если обычную то программа переведёт вам её в битли.)

Вот пример того как нужно запускать код:
>python main.py -l https://github.com/Zakhar514?tab=repositories

Это мы вписываем в командную строку. И вот что нам выведет программа:

>Битлинк bit.ly/3C1roov

Если ввести теперь эту ссылку в команд. строку, то код будет считать количество кликов:

Пишем то же самое только с битли-ссылкой: 
>python main.py -l bit.ly/3C1roov

И нам выводит:
>Количество переходов по ссылке битли:  0


## Сделано с помощью 

* [Devman](https://dvmn.org/) - Devman — практика Python. Курс программирования
* [Docs Python](https://docs.python.org/3/howto/argparse.html) - Argparse Tutorial
* [PythonRu](https://pythonru.com/biblioteki/kratkoe-rukovodstvo-po-biblioteke-python-requests) - Краткое руководство по библиотеке Python Requests

## Благодарности

Всем тем кто помогал писать код и этот README.
