# Grantalytics
Проект GrantInsight представляет собой исследование зависимостей вероятности получения грантов для организаций от различных факторов, таких как регион регистрации, возраст организации и её экономическая деятельность.

### Проект: Анализ возможности получения грантов для некоммерческих организаций

#### Описание проекта:

Этот проект направлен на анализ данных некоммерческих организаций с целью определения возможности получения грантов от государства или участия в государственных контрактах. Мы провели обширный анализ данных, включающий в себя исследование зависимостей от различных факторов, таких как регион регистрации организации, возраст организации, экономическая деятельность и другие характеристики.

#### Шаги проекта:

1. **Загрузка данных:**
   - Мы начали с загрузки данных о некоммерческих организациях, включая информацию о регионе регистрации, возрасте организации, экономической деятельности и других характеристиках.

2. **Очистка и предобработка данных:**
   - Произвели очистку данных от пропущенных значений и аномалий.
   - Преобразовали категориальные переменные и извлекли необходимые признаки.

3. **Анализ зависимостей:**
   - Провели статистический анализ зависимости вероятности получения грантов от различных факторов, таких как регион, возраст и экономическая деятельность.

4. **Моделирование:**
   - Создали модель машинного обучения (в данном случае, логистическую регрессию), чтобы предсказать вероятность получения грантов.

5. **Оценка производительности модели:**
   - Оценили производительность модели на основе метрик, таких как точность, матрица ошибок и отчет о классификации.

6. **Дополнительные анализы:**
   - Провели дополнительные анализы, рассматривая другие признаки и их влияние на вероятность получения грантов.

7. **Выводы и рекомендации:**
   - Сделали выводы на основе проведенного анализа и предоставили рекомендации для дальнейших шагов.

#### Инструкции по запуску:

1. Клонируйте репозиторий на свой локальный компьютер.
2. Убедитесь, что у вас установлены все необходимые библиотеки, указанные в файле зависимостей.
3. Запустите Jupyter Notebook или скрипт для последовательного выполнения шагов проекта.

#### Зависимости:

- Python 3.x
- Jupyter Notebook
- Библиотеки Python: pandas, numpy, matplotlib, seaborn, scikit-learn

#### Структура проекта:

- `data/`: Папка с данными.
- `notebooks/`: Jupyter Notebooks с пошаговым выполнением проекта.
- `README.md`: Файл с описанием проекта и инструкциями по запуску.
