# FastReg
Данный скрипт помогает произвесты быстрое восстоновление компьтеров 01AlemSchool из вашего облака (GitHub) за несколько строчек терминала:
 - Полность восттановить состояние вашего браузера из облока
 - Востановит SSH ключи из придедущей сессий
 - Автоматический клонирует заданные вами репозиторий
 - Установит пароль вам на компьтер
 - Начнёт раздавать wi-fi с вашего компьтера

<!-- ## Содержание
- [Технологии](#технологии)
- [Начало работы](#начало-работы)
- [Тестирование](#тестирование)
- [Deploy и CI/CD](#deploy-и-ci/cd)
- [Contributing](#contributing)
- [To do](#to-do)
- [Команда проекта](#команда-проекта)

## Технологии
- [GatsbyJS](https://www.gatsbyjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- ... -->

## Использование
Для начала использования вам вначале нужно сделать ряд надстроек

1) Войдите в [GitHub](https://github.com/login) аккаунт 

2) Созддайте открытый репозиторий и клонируйте его к себе на компьтер в корневой раздел

```sh
cd ~/
git clone https://github.com/NickName/RepoName
```

3) Клонируйте данный репозиторий в корневой раздел компьютера
```sh
cd ~/
git clone https://github.com/p0n41k/FastReg
```


Установите npm-пакет с помощью команды:
```sh
$ npm i your-awesome-plugin-name
```

И добавьте в свой проект:
```typescript
import { hi } from "your-awesome-plugin-name";

hi(); // Выведет в консоль "Привет!"
```

## Разработка

### Требования
Для установки и запуска проекта, необходим [NodeJS](https://nodejs.org/) v8+.

### Установка зависимостей
Для установки зависимостей, выполните команду:
```sh
$ npm i
```

### Запуск Development сервера
Чтобы запустить сервер для разработки, выполните команду:
```sh
npm start
```

### Создание билда
Чтобы выполнить production сборку, выполните команду: 
```sh
npm run build
```

## Тестирование
Какие инструменты тестирования использованы в проекте и как их запускать. Например:

Наш проект покрыт юнит-тестами Jest. Для их запуска выполните команду:
```sh
npm run test
```

## Deploy и CI/CD
Расскажите, как развернуть приложение. Как запустить пайплайны и т.д.

## Contributing
Как помочь в разработке проекта? Как отправить предложение или баг-репорт. Как отправить доработку (оформить pull request, какие стайлгайды используются). Можно вынести в отдельный файл — [Contributing.md](./CONTRIBUTING.md).

## FAQ 
Если потребители вашего кода часто задают одни и те же вопросы, добавьте ответы на них в этом разделе.

### Зачем вы разработали этот проект?
Чтобы был.

## To do
- [x] Добавить крутое README
- [ ] Всё переписать
- [ ] ...

## Команда проекта
Оставьте пользователям контакты и инструкции, как связаться с командой разработки.

- [Богдан Звягинцев](tg://resolve?domain=bzvyagintsev) — Front-End Engineer

## Источники
Если вы чем-то вдохновлялись, расскажите об этом: где брали идеи, какие туториалы смотрели, ссылки на исходники кода. 