# congenial-engine
## python-game-engine

## Описание
Это проект 3D и 2D движка для разработки 2D и 3D игр на Python с графическим интерфейсом. Движок включает в себя основные компоненты для рендеринга, физики и графического интерфейса проект не тестировался и я не знаю или он работает мне лень проверять 

## Структура проекта
```
python-game-engine
├── src
│   ├── engine
│   │   ├── core.py          # Основной класс GameEngine для управления игровым циклом
│   │   ├── renderer         # Модуль рендеринга
│   │   │   ├── renderer2d.py # Класс Renderer2D для 2D рендеринга
│   │   │   └── renderer3d.py # Класс Renderer3D для 3D рендеринга
│   │   ├── physics          # Модуль физики
│   │   │   └── physics_engine.py # Класс PhysicsEngine для симуляции физики
│   │   └── gui              # Модуль графического интерфейса
│   │       └── gui_system.py # Класс GuiSystem для управления элементами интерфейса
│   ├── utils                # Утилиты
│   │   └── math_utils.py    # Утилиты для математических операций
│   └── main.py              # Точка входа приложения
├── tests                    # Модуль тестирования
│   └── test_engine.py       # Юнит-тесты для движка
├── requirements.txt         # Зависимости проекта
└── setup.py                 # Скрипт настройки для упаковки проекта
```

## Установка
1. Клонируйте репозиторий:
   ```
   git clone https://github.com/rostic7997/congenial-engine.git
   ```
2. Перейдите в директорию проекта:
   ```
   cd python-game-engine
   ```
3. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```

## Использование
Запустите приложение:
```
python src/main.py
```

## Лицензия
Этот проект лицензирован под MIT License.
