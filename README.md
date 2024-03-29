# Требования к окружению

node - 14.14.0
npm - 6.14.8 (по идее установится вместе с node 14.14.0 автоматически, если нет то установить самостоятельно)

Для переключения между версиями node можно использовать nvm

# Требования к процессу

- Важно сохранять структуру проекта.
- Учитывать возможное переполнение контента (при локализации)
- Соблюдать разметку для локализации (использовать lang/en.json)

# По локализации

- в дирректории /lang есть пример json для EN
- в json для EN вносится текст, поля и значения задаются верстальщиком в соответствии с макетом и необходимостью для верстки
- затем EN json мы выгружаем в систему, где наши локализаторы переводят его на соответствующие языки

# Как запустить проект

```
    nvm use 14.14.0 // используем node 14.14.0 и npm 6.14.8 в корневой папке
    npm i // собираем пакеты в корневой папке
    npm run build // собрать лендинг корневой папке

    sudo npm i -g live-server // установить live-server
    live-server // запустить live-server в папке public
    npm run watch // в корневой папке - режим watch
```

# Библиотеки, которые наши дизайнеры, верстающие лендинги, используют

- AOS (анимация при скролле) - https://michalsnik.github.io/aos/
- jQuery - используется на большинстве лендингов, которые собираются с Gulp
- Bootstrap grid - https://getbootstrap.com/docs/4.0/layout/grid/
- Siema (слайдеры) - https://pawelgrzybek.github.io/siema/ (так же есть несколько лендингов, которые используют slick - https://kenwheeler.github.io/slick/ или swiper - https://swiperjs.com/)
- Lottie (json анимации) - https://lottiefiles.com
- Rellax (паралакс) - https://dixonandmoe.com/rellax/
