# Mesto — Sprint 1

## Описание

Ручное тестирование веб‑сервиса **Mesto**: прогон тест-кейсов, анализ найденных дефектов и выводы по готовым требованиям.

Цель работы — оценить качество реализации ключевых пользовательских сценариев (просмотр и редактирование профиля, работа с карточками) и зафиксировать текущее состояние продукта перед релизом.

## Ссылки
- Реализация: https://code.s3.yandex.net/qa/files/mesto/index.html
- Требования: https://praktikum.notion.site/Mesto-9f2cfaa209734d1f8cfa0c0db3d3049f

## Артефакты

- ✅ **Тест-кейсы** — статусы Passed/Failed/Blocked  
  - ✅ [Google Sheets — Test cases](https://docs.google.com/spreadsheets/d/13nzquQs9HWhjU0buZW-GD-v3z_A_sof28SgfXInC4kY/edit?gid=220888493#gid=220888493)  
  - 📁 [sprint1-testcases (GitHub)](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-testcases)

- 🐞 **Баг-репорты** — шаги, ER/AR, окружение  
  - 🐞 [Google Sheets — Bug reports](https://docs.google.com/spreadsheets/d/1yY5eNi8DMjGEhlcMzAAcT_nKohSqs_---3R_lMUR-n4/edit?gid=1186534874#gid=1186534874)  
  - 📁 [sprint1-bugreports (GitHub)](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-bugreports)

- 🔁 **Retest (Sprint 1)** — результаты ретеста дефектов (B1–B15)  
  - 🔁 [Google Sheets — Retest](https://docs.google.com/spreadsheets/d/1mqbbYBXJ6YJSuZtBK-uiI9E6lQDbB0JFdRBtRQpQNGg/edit?gid=379530441#gid=379530441)  
  - 📁 [sprint1-retest (GitHub)](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-retest)


## Итоги
📊 Regression: **17** • 🟢 Passed: **8** • 🔴 Failed: **7** • 🔵 Blocked: **2** • ✅ Rate: **53% (8/15)**  
🔁 Retest: **15** • ✅ Closed: **10** • 🔁 Reopened: **5**

## Scope
- Manual QA, Sprint 1:
  - Regression test run
  - Retest (verification / reopen)

## Окружение
- OS: Windows 11 Pro 21H2
- Browser: Google Chrome 144.0.7559.133

## Ключевые дефекты (High)
- [SP1_TK2](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK2.md) — данные профиля не сохраняются после нажатия “Сохранить”
- [SP1_TK3](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK3.md) — поле “Занятие” пустое при открытии редактирования
- [SP1_TK4](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK4.md) — поле “Имя” пустое при открытии редактирования

## Заблокированные проверки (Blocked)
- [TK-09](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-testcases/testcases/TK-09.md) — невозможно проверить неактивность “Сохранить” при пустом поле “Имя” (поля открываются пустыми) → связано с [SP1_TK3](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK3.md) / [SP1_TK4](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK4.md)
- [TK-17](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-testcases/testcases/TK-17.md) — невозможно проверить автоудаление пробелов, т.к. изменения не сохраняются → связано с [SP1_TK2](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK2.md)

## Вывод
Выявлены дефекты, влияющие на основной пользовательский сценарий редактирования профиля.  
Релиз в текущем состоянии не рекомендован до исправления High-дефектов и повторного регресса.

## Автор
Anatoly Elnikov
