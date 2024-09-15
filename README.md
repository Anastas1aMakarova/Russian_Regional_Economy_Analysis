# Анализ региональной экономики России
### Интерактивная статистика и интеллектуальная аналитика сбалансированности  региональной экономики России на основе Больших данных и блокчейн – 2024

## Актуальность составления дашборда
Высокая степень регионализации является характерной для России чертой. Хотя с одной стороны это поддерживает многообразие общества, с другой — вызывает диспропорции в экономике и неустойчивость. В свою очередь это сказывается и на стратегии развития экономики. На данный момент перед Россией стоит цель перехода в категорию развитых стран, для этого необходимо обеспечить сбалансированность региональной экономики (Стратегия пространственного развития России), в том числе сгладить различия в уровне и темпе развития регионов. Для составления экономической стратегии важно провести качественный анализ региональной экономики, однако этому препятствует дефицит и бессистемность статистики. Анализ региональной экономики на основе комплексного подхода с использованием современных методов исследования должен решить данную проблему и помочь эффективно и качественно анализировать и выстраивать экономическую политику.


## Актуальные вопросы, решаемые дашбордом
**1.Неравномерность развития:**
Регионы России отличаются по уровню развития, доходам, инвестиционной привлекательности и т.д. Анализ региональной экономики помогает выявить эту неравномерность и разработать меры для ее устранения.

**2.Влияние внутренних и внешних факторов**
Экономика каждого региона в разной степени испытывает на себе влияние внутренних и внешних проблем страны. Анализ экономической ситуации в определенном временном периоде позволяет оценить это влияние и разработать стратегии адаптации.

**3.Повышение конкурентоспособности:**
Регионы конкурируют между собой за инвестиции и квалифицированные кадры. Анализ региональной экономики позволяет оценить конкурентоспособность региона, а также разработать меры по ее повышению.

**4.Обеспечение устойчивого развития:**
Региональная экономика должна обеспечить не только экономический рост, но и социальное благополучие населения. Анализ экономики региона позволяет оценить уровень его устойчивости и разработать меры повышения.

**5.Выравнивание бюджетной обеспеченности:** 
Обеспечение равного доступа к бюджетным ресурсам для всех регионов, невозможно без тщательного анализа их финансового положения и потребности в средствах.

**6.Оценка эффективности региональной политики:**
Анализ региональной экономики позволяет оценить эффективность реализуемой региональной политики, выявить ее сильные и слабые стороны, скорректировать курс развития при необходимости.

**7.Реализация национальных проектов:** 
Эффективная реализация национальных проектов в регионах требует оценки их влияния на экономику конкретных регионов.

**8.Распределение полномочий:** 
Разграничение полномочий между федеральным центром и регионами требует тщательного анализа экономического потенциала и возможностей каждого региона.

## Как собирались данные
Сайт https://datasets-isc.ru/ предоставляет ценный набор данных, который может быть использован для создания информативного и актуального дашборда. Нами был взят датасет [«Интерактивная статистика и интеллектуальная аналитика сбалансированности региональной экономики России на основе Больших данных и блокчейн – 2024» ](https://datasets-isc.ru/data-2/747-data-set-interaktivnaya-statistika-i-intellektualnaya-analitika-sbalansirovannosti-regionalnoj-ekonomiki-rossii-na-osnove-bolshikh-dannykh-i-blokchejn-2021). В датасете объединена статистика по теме сбалансированности региональной экономики России за 2005-2023 гг., отражающая уровень и потенциал социально-экономического развития российских регионов. В датасете содержатся показатели, большинство из которых предоставлено Росстатом, вот ключевые из них:
| Название                                        | Описание                                                                                                          |
|-------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| ВВП                                             | Валовой внутренний продукт является одним из важнейших показателей экономического развития региона                |
| Воронки отсталости                              | Отражают собой механизм потери отдельными регионами возможностей для развития вследствие отставания во времени    |
| Доходы регионального бюджета                    | Денежные поступления, складывающиеся из доходов от региональных налогов и сборов                                  |
| Расходы регионального бюджета                   | Денежные средства, направляемые из бюджетного фонда на финансовое обеспечение выполняемых задач и функций региона |
| Сальдо                                          | Сальдо регионального бюджета представляет собой соотношение между доходной и расходной частями бюджета            |
| Доля инновационно активных организаций          | Доля компаний, занимающихся инновациями                                                                           |
| Доля инновационных продуктов                    | Доля инновационной продукции региона, созданной с использованием результатов интеллектуальной деятельности        |
| Инвестиции в основной капитал на душу населения | Показывает объем инвестиций в основной капитал, что является индикатором будущего экономического роста            |

## Подготовка данных
Для дальнейшего анализа данные были обработаны и подготовлены. С получившимся датасетом можно ознакомиться [по ссылке](https://docs.google.com/spreadsheets/d/e/2PACX-1vRWse4Knyb73VWoIywsaDSMAbRmHnJKhYlfPqM7sUOdk9hlJam1kZIRSmIjqJbjZKMg-OfWP37HROJu/pubhtml)


## Визуализация данных
Код для визуализации данных был написан нами с использованием средств python. Полностью код можно посмотреть на Githab [Макарова](https://github.com/Anastas1aMakarova/Russian_Regional_Economy_Analysis) и Githab [Калинина](https://github.com/Kal1n1na/Russian_Regional_Economy_Analysis)

<!--Установка-->
## Резвертывание
У вас должны быть установлен [Репозиторий](https://github.com/Anastas1aMakarova/Russian_Regional_Economy_Analysis)

1. Клонирование репозитория 

```git clone https://github.com/Anastas1aMakarova/Russian_Regional_Economy_Analysis.git```

2. Переход в директорию Russian_Regional_Economy_Analysis

```cd Russian_Regional_Economy_Analysis```

3. Создание виртуального окружения

```python3 -m venv venv```

4. Активация виртуального окружения

```source venv/bin/activate```

5. Установка в виртуальное окружение библиотеку компонентов начальной загрузки
   
```pip install dash-bootstrap-components```
   
6. Запуск скрипта для демонстрации возможностей 

```python3 app_part3.py ```

## Размещение в интернете
Полученный многостраничный дашборд было решено разместить в интернете для публичного доступа. Для размещения был выбран ресурс [PythonAnywhere](https://www.pythonanywhere.com/) — онлайн-интегрированная среда разработки (IDE) и служба веб-хостинга (PaaS), основанная на языке программирования Python. На сервисе pythonanywhere.com можно получить бесплатное место на диске и удобные настройки для развертывания проекта.

## Результат
Самостоятельно исследовать и ознакомиться с проектом можно [**по ссылке**](https://anastasiamakarovakalininajulia.pythonanywhere.com/)
