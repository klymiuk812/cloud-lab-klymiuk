# NotebookLM — фактичне виконання

Notebook створено у Gemini Notebook під назвою **Lab_Klymiuk_10**.

## Додані джерела

1. [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
2. [README проєкту в GitHub](https://raw.githubusercontent.com/klymiuk812/cloud-lab-klymiuk/main/README.md)
3. [View and analyze your app's ratings and reviews — Play Console Help](https://support.google.com/googleplay/android-developer/answer/138230?hl=en)

## Виконані запити та перевірка відповідей

1. **Pandas.** Запитано пояснення `df.groupby("version")["rating"].mean()` з коротким прикладом. Відповідь NotebookLM правильно розклала вираз на групування, вибір поля й агрегацію; до тверджень додано клікабельні номери-цитати.
2. **README.** Запитано назви основних розділів README та їхній зв'язок із запуском у Google Colab. Відповідь послалася на опис, структуру репозиторію, інструкцію запуску, дані, результати, висновки й автора; окремо підтвердила роль кнопки Open in Colab.
3. **Відгуки Play Console.** Запитано, як оцінки й відгуки допомагають визначати проблеми, з фокусом на `Crashes`. Відповідь пов'язала збої з категорією Stability, впливом на рейтинг і пріоритетом виправлення; всі ключові тези мають цитати.

## Докази

Справжні скриншоти джерел і відповідей з цитатами збережено в `docs/execution_evidence/`:

- `notebooklm_sources_answer.png`;
- `notebooklm_googleplay_answer.png`;
- `notebooklm_completed.png`.

Запити не були прийняті без перевірки: фрагменти коду та твердження зіставлено з документацією і фактичним запуском notebook у Google Colab.
