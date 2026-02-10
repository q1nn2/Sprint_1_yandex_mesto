# Mesto — Sprint 1 (Manual QA)

Репозиторий с результатами ручного тестирования веб-сервиса **Mesto**: прогон тест-кейсов, дефекты, выводы по готовым требованиям.

## Ссылки
- Реализация: https://code.s3.yandex.net/qa/files/mesto/index.html
- Требования: https://praktikum.notion.site/Mesto-9f2cfaa209734d1f8cfa0c0db3d3049f

## Артефакты

| Артефакт | Что внутри | Ссылка |
|---|---|---|
| ✅ Тест-кейсы (прогон) | Статусы **Passed/Failed/Blocked** | ✅ [Google Sheets — Test cases](https://docs.google.com/spreadsheets/d/13nzquQs9HWhjU0buZW-GD-v3z_A_sof28SgfXInC4kY/edit?gid=220888493#gid=220888493) |
| 🐞 Баг-репорты | Шаги, ER/AR, окружение | 🐞 [Google Sheets — Bug reports](https://docs.google.com/spreadsheets/d/1yY5eNi8DMjGEhlcMzAAcT_nKohSqs_---3R_lMUR-n4/edit?gid=1186534874#gid=1186534874) |
| 📁 Testcases (GitHub) | Структурированная версия тест-кейсов в ветке | 📁 [sprint1-testcases](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-testcases) |
| 📁 Bugreports (GitHub) | Структурированная версия баг-репортов в ветке | 📁 [sprint1-bugreports](https://github.com/q1nn2/Sprint_1_yandex_mesto/tree/sprint1-bugreports) |

## Scope
- Тип: регрессионное тестирование (Sprint 1)

## Окружение
- OS: Windows 11 Pro 21H2
- Browser: Google Chrome 144.0.7559.133

## Итоги прогона
📊 Total: **17** • 🟢 Passed: **8** • 🔴 Failed: **7** • 🔵 Blocked: **2** • ✅ Rate: **53% (8/15)**

## Ключевые дефекты (High)
- [SP1_TK2](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK2.md) — данные профиля не сохраняются после нажатия “Сохранить”
- [SP1_TK3](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK3.md) — поле “Занятие” пустое при открытии редактирования
- [SP1_TK4](https://github.com/q1nn2/Sprint_1_yandex_mesto/blob/sprint1-bugreports/bugreports/SP1_TK4.md) — поле “Имя” пустое при открытии редактирования

## Вывод
Выявлены дефекты, влияющие на основной пользовательский сценарий редактирования профиля.  
Релиз в текущем состоянии не рекомендован до исправления High-дефектов и повторного регресса.

## Автор
Anatoly Elnikov
