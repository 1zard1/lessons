# Какой процент кода нужно покрывать тестами?
Нужно стремиться к 70-80%, но держать в голове, что на практике покрытие будет на 10-15% меньше, чем запланировал.

# Какие инструменты для тестирования существуют?
- библиотека pytest
- Postman для тестирования API
- Selenium для автоматизации ручного тестирования
- Linter для проверки Code Style

# Какие виды тестирования существуют в backend проектах на Python?
- unit-тесты
- интеграционные тесты
- mock-тестирование

# Что такое unit-тесты? Зачем они нужны?
Unit-тесты проверяют работоспособность отдельных модулей проекта.

# Что такое интеграционные тесты? Зачем они нужны?
Интеграционные тесты - это вид автоматизированных тестов, проверяют, как работают отдельные компоненты программы вместе. Они могут включать в себя тестирование взаимодействия между различными модулями, тестирование работоспособности баз данных или внешних систем, а также другие сценарии использования, соответствующие реальным условиям выполнения программного кода. Целью интеграционных тестов является проверка правильности взаимодействия компонентов программного обеспечения и демонстрация работоспособности системы в целом.

# Что такое mock-тесты? Зачем они нужны?
Mock-тесты (или мокирование) — это метод тестирования программного обеспечения, при котором реальные компоненты системы заменяются их имитациями, называемыми моками (mocks). Эти моки позволяют изолировать тестируемый код от внешних зависимостей, что делает тесты более предсказуемыми и быстрыми.

Зачем нужны mock-тесты?
  - Изоляция: Моки позволяют тестировать код в изоляции от внешних систем, таких как базы данных, веб-сервисы или файловые системы.
  - Скорость: Тесты с моками выполняются быстрее, так как не требуют взаимодействия с реальными внешними системами.
  - Контроль над данными: Моки позволяют задавать конкретные возвращаемые значения и сценарии, что упрощает проверку различных условий и обработку ошибок.
  - Надежность: Тесты становятся более надежными, так как не зависят от состояния внешних систем, которые могут быть недоступны или изменяться со временем.
