# tg_bot_btc_usd
## Данный репозиторий содержит проект по созданию простого телеграмм бота, возвращающего текущую цену Bitcoin (BTC) в долларах (usd)

|Название проекта                     |Направление деятельности   |Используемые инструменты     | Задачи проекта                                                      |
|:------------------------------------|:--------------------------|:----------------------------|:--------------------------------------------------------------------|
|[Telegram bot for btc usd](https://github.com/sx118828/TgBotLlm/blob/main/tg_bot_btc_usd.py)|`Python developer`|*telebot*, *requests*, *wheel*|Развернуть telegram бота, возвращабщего цену в долларах, по запросу 'price' BTC |

## Подробное руководство

### A. Развернуть на локальном компьютере
1. Открыть терминал Linux (Alt + T) и ввести команду `pwd`, посмотреть директорию в которой находимся.
2. Ввести `cd /home/` чтобы перейти в директорию - home.
3. Ввести `sudo -s` для получения прав root.
4. Обновить пакеты вводом команд `apt install sudo`, `sudo apt update`, `sudo apt upgrade -y`.
5. Установить python `sudo apt install python3-venv`.
6. Клонировать c github репозиторий в home `git clone https://github.com/sx118828/tg_bot_btc_usd.git`.
7. Перейти в папку с клонированным репозиторим `cd tg_bot_btc_usd/`.
8. Создать виртуальное окружение `python3 -m venv venvBOT`.
9. Активировать виртуальное окружение `source venvBOT/bin/activate`.
10. Устанавить библиотеки `pip install requests`, `pip install wheel`, `pip install telebot`.
11. Открыть для редактирования файл с идентификационными данными `nano auth_data_btc_usd.py`, ввести `Y`.
12. Копировать токен, выданный @BotFather и вставить его вместо `<tokem_from_@BotFather>`, далее `Ctrl + O`, `Enter` и `Ctrl + X`.
13. Переименовать файл auth_data_btc_usd.py в auth_data.py командой `mv auth_data_btc_usd.py auth_data.py`.
14. Запустить бота `python3 tg_bot_btc_usd.py`.

### B. Развернуть на сервере
1.	Создаем виртуальную машину (Далее – ВМ, выбрать можно любого провайдера, который вас устраивает, например: [cloud.ru](https://cloud.ru/ru) – имеется хорошая документация и приемлемые цены).
2.	Подключаемся к ВМ, например, через PuTTY по SSH, вводим пароль и попадаем в терминал нашей ВМ.
3.	В терминале ВМ вводим 


###### Данный проект пересекается с проектом на [PythonToday](https://www.youtube.com/watch?v=x-VB3b4pKcU&list=PLqGS6O1-DZLoAADhgzzkvc8ifKsKG4G-T&index=4)

