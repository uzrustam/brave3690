# Инструкция по языку MarkDown

## Стилизация текст
Обычный текст набираем как есть.

Новая строка.

**Полужирный текст**

*Курсив*

## Цитирование в языке MarkDown
> Первый уровень цитирования
>> Второй уровень

## Списки
### Ненумерованный список
* Лист
* Лист
+ Лист 1
+ Лист 2
- Лист 3
- Лист 4

### Нумерованный список
1. Лист
2. Лист

## WEB ссылки
текст [пример ссыллки](http.example.com "Всплывающая подсказка")

## Таблица

| Загаловок | Загаловок |
|-----------|-----------|
| Ячейка    | Ячейка    |
| Ячейка    | Ячейка    |

# Добавим как добавлять картинки в Markdown
Это кот
![Кот](kot.jpg)

## Команда позволяет перемещаться между ветками
``````
git checkout<Имя файла>
``````
##  команда позволяет слить ветки
``````
git merge <имя ветки>
``````
# Удалить уже слитую ветку

``````
git branch -d <имя ветки>
``````

# Увидеть лог коммитов с визуализацией между ними
``````
git log --graph
``````

## Cделать локальную копию удаленного репозитория
``````
git clone
``````
## Cтянуть/выкачать» все изменения из удаленного репозитория на свой компьютер
``````
git pull
``````
## Отправить изменения в удаленный репозиторий
``````
git push
``````