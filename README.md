# Sprint 1 — Test cases run (Mesto)

Ветка содержит результаты прогона тест-кейсов за 1 спринт.

## Ссылки
- ✅ Google Sheets — Test cases: [открыть](https://docs.google.com/spreadsheets/d/13nzquQs9HWhjU0buZW-GD-v3z_A_sof28SgfXInC4kY/edit?gid=220888493#gid=220888493)
- 🐞 Google Sheets — Bug reports: [открыть](https://docs.google.com/spreadsheets/d/1yY5eNi8DMjGEhlcMzAAcT_nKohSqs_---3R_lMUR-n4/edit?gid=1186534874#gid=1186534874)
- 🐞 Ветка с баг-репортами: [sprint1-bugreports](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-bugreports)

## Итоги прогона
📊 Total: **17** • 🟢 Passed: **8** • 🔴 Failed: **7** • 🔵 Blocked: **2** • ✅ Rate: **53% (8/15)**

---

## Прогон тест-кейсов (кликабельно)

| № | Тест-кейс | Статус | ID баг-репорта / причина |
|---:|---|---|---|
| 1 | [TK-01 — Открытие окна редактирования профиля](testcases/TK-01.md) | 🟢 Passed | — |
| 2 | [TK-02 — Обновление полей "Имя" и "Занятие"](testcases/TK-02.md) | 🔴 Failed | [SP1_TK2](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK2.md) |
| 3 | [TK-03 — Отображается текст из блока пользователя в поле "Занятие"](testcases/TK-03.md) | 🔴 Failed | [SP1_TK3](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK3.md) |
| 4 | [TK-04 — Отображается текст из блока пользователя в поле "Имя"](testcases/TK-04.md) | 🔴 Failed | [SP1_TK4](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK4.md) |
| 5 | [TK-05 — Закрытие окна редактирования профиля](testcases/TK-05.md) | 🟢 Passed | — |
| 6 | [TK-06 — Отображение полей окна редактирования профиля](testcases/TK-06.md) | 🟢 Passed | — |
| 7 | [TK-07 — Ошибка при вводе >200 символов в поле "Занятие"](testcases/TK-07.md) | 🔴 Failed | [SP1_TK7](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK7.md) |
| 8 | [TK-08 — Ошибка при вводе <2 символов в поле "Имя"](testcases/TK-08.md) | 🔴 Failed | [SP1_TK8](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK8.md) |
| 9 | [TK-09 — При пустом поле "Имя" кнопка "Сохранить" не активна](testcases/TK-09.md) | 🔵 Blocked | [SP1_TK3](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK3.md) / [SP1_TK4](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK4.md) |
| 10 | [TK-10 — "Сохранить" не активна при невалидном "Занятие"](testcases/TK-10.md) | 🟢 Passed | — |
| 11 | [TK-11 — "Сохранить" не активна при невалидном "Имя"](testcases/TK-11.md) | 🟢 Passed | — |
| 12 | [TK-12 — Окно редактирования профиля по центру страницы](testcases/TK-12.md) | 🟢 Passed | — |
| 13 | [TK-13 — При пустом поле "Занятие" кнопка "Сохранить" не активна](testcases/TK-13.md) | 🟢 Passed | — |
| 14 | [TK-14 — Ошибка при вводе <2 символов в поле "Занятие"](testcases/TK-14.md) | 🔴 Failed | [SP1_TK14](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK14.md) |
| 15 | [TK-15 — Ошибка при вводе >40 символов в поле "Имя"](testcases/TK-15.md) | 🔴 Failed | [SP1_TK15](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK15.md) |
| 16 | [TK-16 — "Сохранить" активна при валидных данных](testcases/TK-16.md) | 🟢 Passed | — |
| 17 | [TK-17 — Автоудаление пробелов при сохранении в конце полей](testcases/TK-17.md) | 🔵 Blocked | [SP1_TK2](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK2.md) |
