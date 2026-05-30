# Deep Learning Portfolio

Портфолио учебно-практических проектов по машинному обучению, глубокому обучению, компьютерному зрению, NLP и LLM/RAG.

## Содержание

### 1. IMDB Sentiment Classification
Классификация отзывов к фильмам на положительные и отрицательные с использованием transfer learning и трансформерной модели.

**Стек:** Python, TensorFlow, Hugging Face Transformers, Google Colab  
**Результат:** Validation Accuracy **0.9324**, Test Accuracy **0.9354**

Папка проекта: [`17-imdb-sentiment-transformers`](./17-imdb-sentiment-transformers)

---

### 2. Cats vs Dogs Classification with MobileNet
Классификация изображений кошек и собак с использованием полного датасета, data augmentation, transfer learning и fine-tuning MobileNet.

**Стек:** Python, TensorFlow, Keras, Google Colab  
**Результат:** Validation Accuracy **0.9833**, Test Accuracy **0.9792**

Папка проекта: [`18-cats-vs-dogs-mobilenet`](./18-cats-vs-dogs-mobilenet)

---

### 3. Stanford Dogs Classification with EfficientNetV2
Классификация пород собак на наборе данных Stanford Dogs с использованием EfficientNetV2 и Keras 3.

**Стек:** Python, TensorFlow, Keras 3, Google Colab  
**Результат:** Train Accuracy **0.9961**, Validation Accuracy **0.9926**, Test Accuracy **0.9894**

Папка проекта: [`19-stanford-dogs-efficientnetv2`](./19-stanford-dogs-efficientnetv2)

---

### 4. Нейро-помощник программиста
RAG-нейро-сотрудник для фриланс-разработчика: анализирует заявки клиентов, формирует уточняющие вопросы, предлагает техническое решение, оценивает сроки/стоимость и готовит ответ заказчику.

**Стек:** Python, OpenAI API, LangChain, ChromaDB, Gradio, Google Colab  
**Результат:** рабочий RAG-пайплайн: Google Docs → структурированные фрагменты → ChromaDB → LLM-ответ → Gradio UI

Папка проекта: [`20-neuro-employee-rag-gradio`](./20-neuro-employee-rag-gradio)

---

### 5. Saiga Mistral 7B GGUF: генерация и оценка качества
Запуск русскоязычной LLM Saiga Mistral 7B в квантованном формате GGUF, генерация 3 шуток и базовая оценка качества ответов на датасете ru_turbo_saiga.

**Стек:** Python, Hugging Face, llama-cpp-python, GGUF, Sentence Transformers, Google Colab  
**Результат:** модель `model-q4_K.gguf` успешно запущена на Tesla T4; получена Accuracy **80%** на 5 тестовых примерах по cosine similarity

Папка проекта: [`21-saiga-mistral-gguf-evaluation`](./21-saiga-mistral-gguf-evaluation)

## Ключевые навыки

- подготовка, очистка и разбиение датасетов;
- аугментация изображений;
- transfer learning и fine-tuning;
- работа с TensorFlow / Keras / Keras 3 / Transformers;
- построение reproducible pipeline в Google Colab;
- разработка RAG-сценариев с векторной базой знаний;
- создание интерфейсов для ML/LLM-приложений через Gradio;
- анализ качества моделей на train / validation / test;
- запуск локальных LLM в формате GGUF;
- работа с Hugging Face Hub и Datasets;
- базовая оценка качества LLM через cosine similarity.

## Структура 

```text
.
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ LICENSE
├─ UPLOAD_CHECKLIST.md
├─ 17-imdb-sentiment-transformers/
│  ├─ README.md
│  ├─ notebook/
│  ├─ reports/
│  └─ images/
├─ 18-cats-vs-dogs-mobilenet/
│  ├─ README.md
│  ├─ notebook/
│  ├─ reports/
│  └─ images/
├─ 19-stanford-dogs-efficientnetv2/
│  ├─ README.md
│  ├─ notebook/
│  ├─ reports/
│  └─ images/
├─ 20-neuro-employee-rag-gradio/
│  ├─ README.md
│  ├─ notebook/
│  └─ reports/
└─ 21-saiga-mistral-gguf-evaluation/
   ├─ README.md
   ├─ notebook/
   ├─ reports/
   └─ images/
```
