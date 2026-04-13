# Автоматизация контроля качества

[![Quality Pipeline](https://github.com/denisok37/quality-demo/actions/workflows/quality.yml/badge.svg)](https://github.com/denisok37/quality-demo/actions/workflows/quality.yml)

## Реализованные этапы
- ✅ Статический анализ (pylint)
- ✅ Unit-тесты (pytest)
- ✅ Проверка покрытия кода (pytest-cov)
- ✅ Quality Gate в CI/CD

## Скриншоты

### Успешный запуск пайплайна
![alt text](image-1.png)

### Сработавший Quality Gate (провал)
![alt text](image-2.png)

## Вывод
Автоматизация позволила автоматически проверять качество кода при каждом коммите. 
Quality Gate останавливает плохой код до попадания в основную ветку. 
Пайплайн ловит ошибки стиля, недостаточное покрытие тестами и уязвимости безопасности.
