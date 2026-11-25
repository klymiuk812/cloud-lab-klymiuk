# Дії у зовнішніх сервісах, які потребують входу до акаунта

Цей проєкт повністю підготовлений локально, але наведені нижче дії не можуть бути виконані без авторизованого облікового запису GitHub, Google/NotebookLM та напарника. Не створюйте фіктивні скриншоти чи посилання.

1. Створіть на GitHub репозиторій `cloud-lab-klymiuk`, додайте цей каталог і виконайте push у `main`.
2. Замініть посилання бейджа Open in Colab у README на:
   `https://colab.research.google.com/github/<login>/cloud-lab-klymiuk/blob/main/notebooks/lab_analysis.ipynb`
3. У Colab відкрийте notebook з GitHub і змініть `DATA_PATH` на raw URL CSV: `https://raw.githubusercontent.com/<login>/cloud-lab-klymiuk/main/data/app_reviews.csv`; після цього запустіть Runtime - Run all.
4. У NotebookLM створіть `Lab_Klymiuk_10`, додайте три URL і виконайте запити з `NotebookLM_prompts.md`; зробіть скриншоти списку джерел та відповіді з посиланнями.
5. Запросіть напарника, створіть щонайменше два issues, окрему гілку, pull request із двома змістовними коментарями, merge та release `v1.0`.

Після виконання цих кроків до звіту можна додати фактичні URL GitHub/Colab/NotebookLM і реальні знімки екрана.
