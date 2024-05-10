# «UI Automator. Автоматизация тестирования Android»

## Решения
### Задание 1
* <a href="https://github.com/Nephedov/7.Mobile-application-testing/blob/main/app/src/androidTest/kotlin/ru/netology/testing/uiautomator/InputTextTest.kt">InputTextTest.kt</a>, с ипользованием UI Automator.
### Задание 2
* <a href="https://github.com/Nephedov/7.Mobile-application-testing/blob/main/.github/workflows/android.yml">android.yml</a> - настройки запуска для Github Actions.
## Что было сделано
### Задание 1
* Построен и запущен проект на эмуляторе Android Studio.
* Реализован класс с инструментальными автотестами
  <a href="https://github.com/Nephedov/7.Mobile-application-testing/blob/main/app/src/androidTest/kotlin/ru/netology/testing/uiautomator/InputTextTest.kt">InputTextTest.kt</a>, с ипользованием UI Automator.
### Задание 2
* Поключен Github Actions и реализован <a href="https://github.com/Nephedov/7.Mobile-application-testing/blob/main/.github/workflows/android.yml">android.yml</a>.

---
---


## Описание Задания 1. «UI Automator»

Ваша задача — добавить два теста:
- тест на попытку установки пустой строки;
- тест на открытие текста в новой Activity.

**Первый тест** должен устанавливать в поле ввода пустой текст и осуществлять нажатие на кнопку изменения текста. После нужно проверить, что текст в TextView остался прежним.

**Второй тест** должен устанавливать в поле ввода непустой текст и осуществлять нажатие на кнопку запуска новой Activity. Затем он должен дождаться появления Activity на экране и в качестве результата сравнить содержимое TextView с текстом, который был установлен в поле ввода.

Для определения ID у TextView, принадлежащего второй Activity, рекомендуем использовать инструмент UI Automator Viewer.

## Описание задания 2. «GitHub Actions»

После выполнения первой задачи добавьте полученный код в репозиторий на GitHub. Второй задачей будет настройка инструмента GitHub Actions для этого репозитория.
