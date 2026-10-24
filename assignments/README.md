# Учебные задания

Результаты семинаров команды 403 (Sansara).

| Семинар | Файлы | Связанные docs |
|---|---|---|
| С5. Истории, RICE, план | [`S5_403_product_book.md`](S5_403_product_book.md), [`S5_403_draft.json`](S5_403_draft.json) | [`docs/04_mvp_and_backlog/`](../docs/04_mvp_and_backlog/), [`docs/05_delivery/work_plan.md`](../docs/05_delivery/work_plan.md) |
| С10. Метрики качества ML-моделей | [`notebooks/team_403_metrics.ipynb`](../notebooks/team_403_metrics.ipynb), данные [`data/raw/seminar_10/`](../data/raw/seminar_10/), зависимости [`notebooks/requirements.txt`](../notebooks/requirements.txt) | [`docs/07_analytics/ml_metrics.md`](../docs/07_analytics/ml_metrics.md) |

### С10 — кратко

- Варианты: классификация 3 (спам), регрессия 8 (LTV), рекомендации 9 (товары) — по строке «3» таблицы распределения. Соответствие кода команды 403 этой строке — **допущение, требует подтверждения преподавателя**; вариант меняется одной переменной `VARIANTS` в ноутбуке, все 10 вариантов посчитаны в приложении А.
- Сдача: файл `team_403_metrics.ipynb` (с сохранёнными результатами ячеек) через форму семинара.
- Техническая метрика, выбранная для Sansara: **Precision@10** Matching Engine (+ Recall@10, NDCG@10; ограничение — 0 несовместимых офферов). North Star Metric не меняется — GMV завершённых сделок.

JSON-черновик можно загрузить в HTML-шаблон семинара 5 (кнопка «Загрузить JSON»).
