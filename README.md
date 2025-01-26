# EduMatchAI - Инновационный программный модуль для подбора образовательных курсов

## Описание проекта

Данный проект представляет собой **готовый программный модуль** с использованием искусственного интеллекта для нахождения наиболее релевантных образовательных курсов GeekBrains на основе вакансий с сайта HH.ru. Это мощный инструмент для автоматизации анализа вакансий и улучшения пользовательского опыта, позволяя строить персонализированные рекомендации для профессионального обучения.

### Актуальность

Современные пользователи сталкиваются с трудностями при выборе подходящих образовательных курсов из огромного множества предложений на образовательных платформах. Этот модуль упрощает процесс формирования индивидуальной траектории обучения, помогая пользователям приобрести знания и навыки, необходимые для достижения желаемой профессии.

### Основной функционал

- **Анализ вакансий с сайта HH.ru**: извлечение требований к кандидатам и их обработка.
- **Подбор образовательных курсов**: определение, какая программа обучения соответствует запросам пользователя и требованиям рынка труда.
- **Рекомендации для профессионального развития**: персонализированный подбор курсов, образовательных продуктов и других материалов.

### Особенности

- Использование передовых алгоритмов искусственного интеллекта.
- Высокая релевантность предложенных курсов за счёт анализа актуальных данных.
- Удобство в использовании и экономия времени пользователей.

## Установка и запуск

**Наше решение разделено на две ключевые части. Первая часть включает в себя подробное руководство по развёртыванию без необходимости взаимодействия с интерфейсом, что обеспечивает быстрое и эффективное тестирование. Вторая часть предоставляет подробные инструкции по развертыванию решения с использованием интерфейса, обеспечивая при этом максимальную удобство и интуитивную навигацию.**

***Часть 1:***
----------

*1. Загрузите репозиторий на свой компьютер и откройте её в вашей предпочитаемой среде разработки (IDE).* 

*2. Откройте терминал в IDE и введите туда следующую команду:* 

```python
python -m venv .venv
```
*3. Дождитесь создание папки `.venv` затем введите следующую команду:*

```python
.\.venv\Scripts\activate
```
*4. После активации установите все библиотеки (весрия python==3.10+) при помощи данной команды:*

```python
pip install -r requirements.txt
```

*5. Дождитесь установки всех библиотек и введите следующую команду.*

```python
pip install parse_hh_data==0.1.14
```

*6. Прекрасно! Теперь в терминале введите команду для перехода к основной папке с кодом проекта.*

```shell
cd src 
```

*7. Для запуска сервиса, введите следующую команду.*

```python
streamlit run src/app.py
```


<p align="center">
    <img src="./entry_streamlit_service.jpg" alt="Логотип проекта" width="900" style="display: inline-block; vertical-align: middle; margin-right: 10px;"/>  <br/>
    Начальная страница сервиса
</p>




# Пример работы сервиса

***Часть 1:***

<p align="center">
    <img src="./1_entry.png" alt="Логотип проекта" width="900" style="display: inline-block; vertical-align: middle; margin-right: 10px;"/>  <br/>
    Поиск образовательных курсов по представленным данным
</p>

***Часть 2:***

<p align="center">
    <img src="./2_search.png" alt="Логотип проекта" width="900" style="display: inline-block; vertical-align: middle; margin-right: 10px;"/>  <br/>
    Найденные схожие образовательные курсы
</p>

***Часть 3:***

<p align="center">
    <img src="./3similars.png" alt="Логотип проекта" width="900" style="display: inline-block; vertical-align: middle; margin-right: 10px;"/>  <br/>
    Следующие по степени схожести образовательные курсы
</p>

***Часть 4:***
**Важно: Процесс немного долгий из-за нагрузки на сервер. Пожалуйста, подождите несколько минут. (Постарайтесь ничего не нажимать в текстовой области**


<p align="center">
    <img src="./verif.png" alt="Логотип проекта" width="900" style="display: inline-block; vertical-align: middle; margin-right: 10px;"/>  <br/>
    Анализ покрытия требований данной вакансии с помощью других образовательных курсов
</p>
