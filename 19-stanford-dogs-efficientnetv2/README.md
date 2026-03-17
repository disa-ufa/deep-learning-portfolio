# Stanford Dogs Classification with EfficientNetV2

## Описание
Проект по классификации пород собак на наборе данных Stanford Dogs с использованием EfficientNetV2 и Keras 3.

## Цель
Провести fine-tuning модели EfficientNetV2 на Stanford Dogs и добиться высокой точности на validation и test.

## Подход
- очистка датасета от повреждённых изображений;
- случайный выбор 10 пород для режима повышенной точности;
- аугментация изображений;
- transfer learning + fine-tuning EfficientNetV2B0;
- обучение в Keras 3.

## Результаты
- Train Accuracy: **0.9961**
- Validation Accuracy: **0.9926**
- Test Accuracy: **0.9894**

## Используемые технологии
- Python
- TensorFlow
- Keras 3
- Google Colab

## Структура папки
- `notebook/` — основной ноутбук
- `reports/` — PDF-отчёт
- `images/` — скриншоты результатов
