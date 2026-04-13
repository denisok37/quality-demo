<img width="656" height="219" alt="image" src="https://github.com/user-attachments/assets/404a7091-a649-4b97-877b-84c04f575bba" /># Автоматизация контроля качества

[![Quality Pipeline](https://github.com/denisok37/quality-demo/actions/workflows/quality.yml/badge.svg)](https://github.com/denisok37/quality-demo/actions/workflows/quality.yml)

## Реализованные этапы
- ✅ Статический анализ (pylint)
- ✅ Unit-тесты (pytest)
- ✅ Проверка покрытия кода (pytest-cov)
- ✅ Quality Gate в CI/CD

## Скриншоты

### Успешный запуск пайплайна


### Сработавший Quality Gate (провал)


## Вывод
Автоматизация позволила автоматически проверять качество кода при каждом коммите. 
Quality Gate останавливает плохой код до попадания в основную ветку. 
Пайплайн ловит ошибки стиля, недостаточное покрытие тестами и уязвимости безопасности.
