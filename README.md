# briskly-test-task
Тестовое задание для компании Briskly.

# Описание
Данное веб-приложение преобразовывает входной json файл с заказом в файл xlsx с валидными товарами из заказа.

# Настройка
Что бы запустить данное приложение необходимо:
1. Клонировать данный репозиторий 

```sh
git clone https://github.com/Dmitridad/briskly-test-task.git
```
2. Открыть терминал в корне клонированного репозитория и выполнить команду

```sh
./up
```
3. После выполнения данной команды, скачаются необходимые Docker образы и запустятся необходимые контейнеры Docker
4. Что бы открыть приложения необходимо в браузере перейти по адресу http://localhost/
5. Далее вы сможете загрузить файл json с заказами и преобразовать его в файл xlsx с последующим экспортом либо локально (/tmp/xls/), либо по FTP
6. Что бы завершить работу приложения необходимо открыть терминал в корне клонированного репозитория и выполнить команду

```sh
./down
```