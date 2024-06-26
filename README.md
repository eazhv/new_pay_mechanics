# A/B–тестирование новой механики оплаты

## Описание проекта

В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. Необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на всех пользователей.

## Основные пункты исследования:

- Подготовка данных

- Выбор метрик

- Выбор статистических критериев для проведения анализа

- Автоматизация для пересчета метрик и построения графиков


## Метрики 

CR в покупку, ARPU, ARPPU


## Выводы и результаты

Механика оплаты повлияла только на доход от платящих пользователей(p-value = 0.00186), но не повлияла на конверсию. Скорее всего на увеличение среднего чека платящих пользователей повлиял не запуск новой механики оплаты, а что-то другое. Рекомендовано не катить новую механику оплаты на всех пользователей, а разобраться, что могло повлиять на увеличение ARPPU и как были сформированы группы для теста.
