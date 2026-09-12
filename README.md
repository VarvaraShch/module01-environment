# Module 01 Environment — Mini Corpus Lab

## Название и цель
Учебный проект по модулю 01: показать, как notebook, runtime, данные и README образуют воспроизводимый артефакт.

## Состав файлов
- `notebooks/lr01_runtime_order_shchegoleva.ipynb` — notebook с порядком ячеек.
- `data/sample_text.txt` — безопасный учебный текст.
- `data/mini_corpus.tsv` — мини-корпус из 3 строк.
- `data/metadata.tsv` — метаданные без персональных данных.
- `version_log.md` — история версий.
- `docs/review_note.md` — peer review.
- `docs/transfer_comparison.md` — сравнение GitHub web и ZIP.
- `docs/reflection.md` — рефлексия.

## Как открыть
1. Открыть Colab/Jupyter.
2. Загрузить папку `module01_environment` или ZIP.
3. Открыть `notebooks/lr01_runtime_order_surname.ipynb`.
4. Выполнить `Restart runtime → Run all`.
5. Проверить, что нет `NameError` и данные читаются по относительному пути `../data/sample_text.txt`.

## Проверка
- Notebook выполняется сверху вниз после `Restart → Run all`.
- README отвечает на вопросы: что это, из чего состоит, как открыть, как проверить, какие ограничения, как менялась версия.
- Данные лежат в `data/`.
- Нет персональных данных, токенов и секретов.

## Ограничения
- Только учебные данные.
- Git CLI не используется.
- Colab runtime временный: переменные исчезают после перезапуска.
- Проект не проверяет внешние библиотеки.

## История версий
См. `version_log.md` и `CHANGELOG.md`.
