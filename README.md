# Subscription-app-cohort-analysis

Приложение - мобильная утилита для сканирования документов. Модель монетизации
подписочная, есть пробный период 7 дней с дальнейшим переходом в оплату 4.99 USD
в неделю. По ссылке ниже выгрузка с базы данных по оформлениям подписок и оплат.
Каждая строка представляет собой отдельное событие (либо оформление пробной
подписки, либо оплата после завершения пробного периода)

1. Провести анализ динамики Daily New Users, Revenue, визуализировать с
помощью графиков
2. Провести когортный анализ (cohorting event - оформление пробного периода,
когорта представляет собой кол-во возможных операций).
a. Рассчитать Retention Rate для когорт
b. Рассчитать LTV для когорт
c. Рассчитать конверсию из триала в оформление подписки
d. Визуализировать результаты с помощью графиков, показать динамику
