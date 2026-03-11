# 📒 Shikimori Info Cards

## 📚 Описание / Description

"Парящая" карточка для Shikimori появляется в нижнем правом углу страницы пользователя для вывода определенной информации. Плавные анимации появления и исчезновения через 15 секунд с таймером в виде полосы.
Анимацию исчезновения можно остановить с помощию наведения курсора на "тело" карточки.

Вид карточки изменяется при помощи класса в первой строке __[div=w-card-container w-card-*]__
The appearance of the card is changed by changing the class in the first line __[div=w-card-container w-card-*]__

Класс имеет 4 вида: / The class has 4 types:

__ warning | info | success | error __

Пример: / Example:

```
[div=w-card-container w-card-warning]

или / or

[div=w-card-container w-card-info]

или / or

[div=w-card-container w-card-success]

или / or

[div=w-card-container w-card-error]

```

## 📦 Установка / Installation

1. Добавить в профиль (блок "О себе) / Add to profile (About me block)

```
[div=w-card-container w-card-error]
[div=w-card-contaent]
[div=w-card-img][/div]
[div=w-card-body]
[div=w-card-title]Технические работы[/div]
[div=w-card-text]Страница находится в разработке. Возможны ошибки и неправильная работа сайта.[/div]
[/div]
[/div]
[/div]
```

2. Подключить файл CSS в "Внешний вид сайта" / Add a CSS file to "Site Appearance"

```
@import url("https://raw.githubusercontent.com/iexdev/shikimori-info-card/refs/heads/main/shikimori-info-card.css");
```
