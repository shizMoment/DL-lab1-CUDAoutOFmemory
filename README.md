## DL-lab1-CUDAoutOFmemory
# Решение ЛР1 по классификации изображений

## Команда:
- Ботунов Даниил (ПМ-31)
- Мыцик Илья (ПМ-31)
- Гирич Лолита (ПМ-32)

## Результат
- **LB**:  0.96391 (это решение невоспроизводимо)
- **Текущее решение**: 0.93955

## Архитектура решения
- **Модель**: convnextv2_base.fcmae_ft_in22k_in1k
- **batch_size**: 16
- **learning_rate**: 1e-5
- **optimizer**: AdamW с weight_decay=0.05
- **loss_fn**: CrossEntropyLoss с label_smoothing=0.1

## Веса модели:
https://disk.yandex.ru/d/_Nw7Be9EJ5QwaQ
