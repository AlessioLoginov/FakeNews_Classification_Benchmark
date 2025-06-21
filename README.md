# FakeNews_Classification_Benchmark

📌 **Описание**  
Этот репозиторий содержит экспериментальное сравнение четырёх подходов к задаче бинарной классификации фейковых новостей:

1. TF-IDF (unigram + bigram)
2. TF-IDF + TruncatedSVD (LSA)
3. TF-IDF с символьными n-граммами (char-level)
4. Нейросеть на PyTorch с Embedding

📈 **Цель**  
Достичь:
- F1 > 0.91 для моделей на `sklearn`
- F1 > 0.52 для модели на `PyTorch`

✅ Цель достигнута во всех вариантах.

---

## 📁 Содержимое

- `FakeNews_Classification_Experiments.ipynb` — основной ноутбук с кодом и комментариями
- `Constraint_Train.csv` — датасет (источник: конкурс по классификации фейковых твитов)
- `README.md` — этот файл

---

## 🧪 Используемые библиотеки

- `pandas`, `matplotlib`, `seaborn`
- `sklearn`
- `torch`
- `tqdm`

---

## 🚀 Запуск

1. Убедитесь, что у вас установлен Python 3.9+
2. Установите зависимости:
```bash
pip install -r requirements.txt
