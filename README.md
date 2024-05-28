# learning_with_teacher

# Персонализация предложений постоянным клиентам

## Примененные библиотеки и технологии
- Pandas, numpy, matplotlib, seaborn, phik, shap, sklearn, pipeline, RandomizedSearchCV, LogisticRegression, KNeighborsClassifier, DecisionTreeClassifier, LinearRegression, SVC

## Цели и задачи проекта
Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений. Нужно промаркировать уровень финансовой активности постоянных покупателей. В компании принято выделять два уровня активности: «снизилась», если клиент стал покупать меньше товаров, и «прежний уровень». Нужно собрать данные по клиентам по группам. В исследование нужно включить дополнительные данные финансового департамента о прибыльности клиента: какой доход каждый покупатель приносил компании за последние три месяца. Используя данные модели и данные о прибыльности клиентов, нужно выделить сегменты покупателей и разработать для них персонализированные предложения.
**Цель**: построить модель, которая предскажет вероятность снижения покупательской активности клиента в следующие три месяца.

Мною были решены следующие **задачи**:
- Предобработка и изучение данных, исследовательский анализ данных, корреляционный анализ;
- Подготовка данных, признаков в пайплайне;
- Обучение моделей - KNeighborsClassifier, DecisionTreeClassifier, LogisticRegression и SVC и и подбор гиперпараметров с помощью RandomizedSearchCV;
- Анализ важности признаков с помощью метода SHAP;
- Сегментация покупателей и рекомандации - графическое и аналитическое исследование группы покупателей, предложения по увеличению покупательской активности.
