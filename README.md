# Praktikum
## Избранные проекты из курса Яндекс.Практикум по специализации Аналитик Данных

Проект | Задачи проекта | Описание проекта | Что было использовано
--- | --- | --- | ---
[ Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/nikolaykydr/praktikum/tree/main/Apartment%20projects)| Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | Проведена предобработка данных. Добавлены новые данные.Построены гистограммы, боксплоты, диаграммы рассеивания | Pandas, Matplotlib, Numpy
[ Анализ пользовательского поведения в мобильном приложении стартапа ](https://github.com/nikolaykydr/praktikum/tree/main/AB%20testing) | На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей|  Pandas, Matplotlib, Numpy, Seaborn, Plotly, A/B-тест
[ Анализ убытков от рекламной компании приложения](https://github.com/nikolaykydr/praktikum/tree/main/Advert_company) | Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным |  Pandas, Matplotlib, Numpy, Статистический тест, кагортный анализ
[Изучение закономерностей, определяющих успешность игр ](https://github.com/nikolaykydr/praktikum/tree/main/AB%20testing) | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры  | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок|  Pandas, Matplotlib, Numpy