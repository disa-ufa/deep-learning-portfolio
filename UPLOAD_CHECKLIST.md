# Upload Checklist

## 1. Переименуй ноутбуки

Используй понятные имена без `Копия блокнота`:

- `imdb_sentiment_transformers.ipynb`
- `cats_dogs_mobilenet.ipynb`
- `stanford_dogs_efficientnetv2.ipynb`

## 2. Разложи файлы по папкам

### 17-imdb-sentiment-transformers
- `notebook/imdb_sentiment_transformers.ipynb`
- `reports/imdb_report.pdf`
- `images/imdb_preview.png`

### 18-cats-vs-dogs-mobilenet
- `notebook/cats_dogs_mobilenet.ipynb`
- `reports/cats_dogs_report.pdf`
- `images/cats_dogs_preview.png`

### 19-stanford-dogs-efficientnetv2
- `notebook/stanford_dogs_efficientnetv2.ipynb`
- `reports/stanford_dogs_report.pdf`
- `images/stanford_dogs_preview.png`

## 3. Добавь файлы из этого пакета в корень репозитория

- `README.md`
- `.gitignore`
- `requirements.txt`
- `LICENSE`
- `UPLOAD_CHECKLIST.md`

## 4. Команды для загрузки в GitHub

```bash
git init
git branch -M main
git add .
git commit -m "Initial portfolio release: IMDB, Cats vs Dogs, Stanford Dogs"
git remote add origin https://github.com/disa-ufa/deep-learning-portfolio.git
git push -u origin main
```

Если репозиторий уже инициализирован:

```bash
git add .
git commit -m "Add three deep learning portfolio projects"
git push
```

## 5. Финальная проверка

Перед push убедись, что:
- в репозитории нет датасетов;
- нет временных папок Colab;
- в README отображаются все три проекта;
- у каждого проекта есть отдельный README;
- ноутбуки открываются из GitHub.
