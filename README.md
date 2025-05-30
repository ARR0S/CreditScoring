# CreditScoring

Модель кредитного скоринга, использующая логистическую регрессию и децильную методологию, позволяющая банкам принимать решения о кредитовании на основе данных, оптимизируя прибыльность и проникновение на рынок.

## Постановка проблемы
Банки и финансовые учреждения часто сталкиваются с проблемами при оценке кредитоспособности заявителей на получение займа. Традиционные методы кредитного скоринга опираются на исторические данные и статистический анализ для определения кредитного балла заемщика. Однако эти методы не всегда эффективны для точного прогнозирования вероятности погашения кредита.

## Обзор решения
Проект «Модель кредитного скоринга» предлагает решение, используя методы машинного обучения для прогнозирования вероятности погашения кредита на основе исторических данных о клиентах. Для построения прогнозной модели используется классификатор Logistic Regression - популярный алгоритм для задач бинарной классификации. Кроме того, он использует децильную методологию для формулирования бизнес-правил для принятия или отклонения новых кредитных заявок, оптимизируя тем самым прибыльность бизнеса и проникновение на рынок.

## Ключевые особенности
- Использует классификатор логистической регрессии для предиктивного моделирования.
- Внедряет децильную методологию для разработки стратегии кредитования.
- Предоставляет данные для принятия обоснованных кредитных решений.
- Предлагает полный набор инструментов с обучающими наборами данных и исходным кодом на языке Python для практического обучения и повторного использования.

## Использование
1. Клонируйте репозиторий на свою локальную машину.
2. Получите доступ к предоставленным наборам данных и файлам исходного кода Python.
3. Используйте Google Colab или аналогичную платформу для построения и анализа моделей.
4. Следуйте пошаговым инструкциям в предоставленных ячейках кода, чтобы понять рабочий процесс проекта.
5. Настройте параметры и пороговые значения модели в соответствии с требованиями вашего бизнеса.
6. Оцените работу модели с помощью таких показателей, как оценка точности и матрица путаницы.
7. Используйте выходные файлы для получения информации и принятия решений о кредитовании на основе данных.

## Начало работы
Чтобы настроить и запустить проект локально, выполните следующие действия:
1. Клонируйте репозиторий:

    ```bash
    git clone https://github.com/ARR0S/CreditScoring.git
    ```

2. Перейдите в каталог проекта:

    ```bash
    cd CreditScoring
    ```

3. Откройте проект в Google Colab или любой среде Python с установленными зависимостями.
4. Следуйте инструкциям в ячейках кода, чтобы построить и проанализировать модель.
5. Обратитесь к файлу README и документации для получения подробной информации об использовании и реализации проекта.

## Источники данных
Наборы данных, используемые для обучения классификатора логистической регрессии, взяты из папки dataset/Dataset_CreditScoring.xlsx.

## Методология
Децильная методология, используемая при разработке стратегии кредитования, предполагает сегментирование клиентской базы на десять равных групп в зависимости от их кредитного скоринга. Такой подход позволяет банку определять приоритетность кредитных решений и эффективно распределять ресурсы.