# Данные проекта Sansara

## Источники данных

| Источник (docx) | Содержание | Файл в репозитории |
|---|---|---|
| Circula Business model.docx | Бизнес-модель, тарифы, unit-экономика (гипотезы), сценарии выручки, roadmap | `raw/business_model.txt` |
| Circula_technical_architecture.docx | Архитектура, matching, метрики, KPI dashboard (пример) | `raw/technical_architecture.txt` |
| mvp.docx | Сценарии продавца/покупателя, scope MVP, экраны P0–P2, matching pipeline | `raw/mvp.txt` |
| Часть Максима.docx | Discovery: проблема, аудитория, конкуренты, рыночный контекст, интервью | `raw/maxim_part.txt` |

> В сырых выгрузках могут встречаться рабочие имена Circula / DeadStock Match. В документации репозитория продукт называется **Sansara**.

Период актуальности конкурентного сравнения: **2 октября 2026**. Рыночные показатели Росстата — **2025 год** (РФ и ЦФО).

### Семинар 10 — учебные датасеты метрик ML

| Параметр | Значение |
|---|---|
| Источник | Архив `resources/metrics_datasets.zip` репозитория курса [amalrik/it-product-management](https://gitverse.ru/amalrik/it-product-management), методичка [`practice/mguide-2-10.md`](https://gitverse.ru/amalrik/it-product-management/content/master/practice/mguide-2-10.md) |
| Дата загрузки | 24 октября 2026 |
| Состав | 10 CSV: `variant_1…5_classification.csv` (`y_true, y_pred, y_score`), `variant_6…8_regression.csv` (`y_true, y_pred`), `variant_9…10_recsys.csv` (`user_id, recommended_items, relevant_items`, списки через `;`) |
| Используются командой | варианты 3, 8, 9 (допущение о соответствии команде 403 — см. [`assignments/README.md`](../assignments/README.md)) |
| Целостность | файлы не изменялись; SHA-256 в `raw/seminar_10/SHA256SUMS`, проверка выполняется в ноутбуке |
| Ограничения | синтетические учебные данные преподавателя; единицы регрессии не указаны («ед. данных»); не являются данными Sansara |

## Структура

- `raw/` — текстовые выгрузки из docx без изменений смысла.
- `raw/seminar_10/` — исходные CSV семинара 10 (метрики ML) и контрольные суммы.
- `processed/` — таблицы для расчётов:
  - `unit_economics_hypothesis.md`
  - `revenue_scenarios.md`
  - `market_context.md`
  - `competitor_sources.md`

## Ограничения

- Цифры unit-экономики и сценариев выручки — **гипотезы**.
- Нет персональных данных респондентов и выгрузок ERP клиентов.
- Официальная монетизация в docs: гибрид Start/Pro/Enterprise (3% / 1,5% / 0,5%); упоминание 5% в `mvp.txt` — черновик, не используется в сдаче.

## Правила использования

Только для учебного проекта. При цитировании указывать первичный файл в `raw/` и дату проверки из `maxim_part.txt`.
