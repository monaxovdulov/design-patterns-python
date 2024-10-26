# Design Patterns in Python

Этот репозиторий содержит коллекцию примеров паттернов проектирования на Python, организованную по основным категориям. Здесь собраны как реализация каждого паттерна, так и примеры использования в реальных сценариях. Репозиторий также включает документацию, диаграммы и пояснительные файлы для каждого паттерна.

## Как начать

Для начала работы рекомендуем изучить следующие файлы из папки `docs/`:

- [Общий обзор паттернов проектирования](docs/overview.md): краткое введение в паттерны проектирования, их назначение и категории.
- [Порождающие паттерны](docs/creational_patterns.md): теория и примеры порождающих паттернов, таких как Singleton и Factory.
- [Структурные паттерны](docs/structural_patterns.md): описание структурных паттернов, таких как Adapter и Decorator.
- [Поведенческие паттерны](docs/behavioral_patterns.md): разбор поведенческих паттернов, таких как Observer и Strategy.


## Структура проекта

### Папки
- **docs/**: Содержит теоретические объяснения для каждой категории паттернов.
  - `overview.md`: Общий обзор паттернов проектирования.
  - `creational_patterns.md`: Теория и примеры порождающих паттернов.
  - `structural_patterns.md`: Теория и примеры структурных паттернов.
  - `behavioral_patterns.md`: Теория и примеры поведенческих паттернов.

- **diagrams/**: Диаграммы для визуализации паттернов, сгруппированные по категориям.

- **creational_patterns/**: Порождающие паттерны, такие как Singleton и Factory.
  - `singleton/`: Папка с примерами и документацией для паттерна Singleton.
    - `README.md`: Описание паттерна Singleton.
    - `implementations/`: Примеры различных реализаций.
      - `basic.py`: Базовый пример.
      - `advanced.py`: Продвинутая реализация.
    - `usage_examples/`: Примеры использования паттерна Singleton в различных сценариях.
      - `example1.py`, `example2.py`: Конкретные примеры использования.
    - `diagram.png`: Диаграмма паттерна Singleton.
  - `factory/`: Папка с аналогичной структурой для паттерна Factory.

- **structural_patterns/**: Структурные паттерны, такие как Adapter и Decorator.
  - `adapter/` и `decorator/`: Папки, организованные так же, как папки паттернов в creational_patterns.

- **behavioral_patterns/**: Поведенческие паттерны, такие как Observer и Strategy.
  - `observer/` и `strategy/`: Папки, организованные так же, как папки паттернов в creational_patterns.

## Как использовать репозиторий

1. **Изучите теорию**:
   Начните с папки `docs/`, где можно ознакомиться с теоретическими файлами для каждой категории паттернов. Они дают общее представление о назначении и применении паттернов.

2. **Изучите конкретные паттерны**:
   Перейдите в папки с интересующими вас паттернами в `creational_patterns/`, `structural_patterns/` или `behavioral_patterns/`. Каждый паттерн содержит файл `README.md` с его объяснением, папку `implementations/` с примерами реализации и `usage_examples/` с примерами применения.

3. **Используйте диаграммы**:
   В папке `diagrams/` вы найдете визуализации каждого паттерна, которые помогут лучше понять их структуру и взаимодействие компонентов.

4. **Запустите код**:
   Чтобы увидеть паттерны в действии, запустите файлы примеров в папках `usage_examples/` для каждого паттерна. Это даст вам представление о том, как паттерн можно использовать в реальных ситуациях.

