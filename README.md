# КРиПИ - Лекции JavaScript

Для работы вам нужен аккаунт на Github и приложение Github http://windows.github.com/

Видео о том как начать работать с Github тут http://video.yandex.ru/users/davydov-mikhail/view/1/

## Проблемы с JSLint

Вот эта сточка в начале кода выключает некоторые проверки у jslit `/*jslint plusplus: true, vars: true, browser: true, devel: true */`

  * plusplus - дает использовать ++ --
  * vars - дает использовать несколько var
  * browser - дает использовать окружение браузера: document, window...
  * devel - дает использовать `alert() prompt() confirm() console.log()`

## Воркфлоу

  1. [браузер] По лекциям находим ссылку на домашнее задание
  2. [браузер] Жмем Fork - делаем точную копию для себя
  3. [gh-client] Жмем Clone - копируюм свою копию к себе на диск
  4. [editor] Редактируем код
  5. [gh-client] Делаем Commit с внятным текстом (я изменил то-то, добавил то-то)
  6. По необходимости повторяем 4-5
  7. [gh-client] Жмем Sync - копия с ПК отправляется в ваш репозиторий
  8. [браузер] Если вы уверены, что все сделали жмите Pull Request
  9. Получем уведомления по почте и вносим изменения по необходимости (4-7, без Pull Request)

## Рекомендуемые редакторы кода

  * [WebStorm](http://www.jetbrains.com/webstorm/) - 30 days free
  * [NetBeans](http://netbeans.org/) - free
  * [Cloud9 IDE](https://c9.io/) - free, Online редактор
  * Notepad++, PSPad, ...

## Не рекомендуемые редакторы кода

  * notepad.exe

## Браузеры

  * Chrome или Yandex
  * Safari 5+
  * Firefox 15+
  * Opera 12+
  * IE 10 - в версии 9 и ниже не работает `"use strict";`