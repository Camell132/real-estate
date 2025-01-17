# Исследование объявлений о продаже квартир

В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

**Цель исследования** — определение влияния различных факторов на стоимость квартиры

**Ход исследования**

Данные о клиентах, которым выдан кредит находятся в файле `real_estate_data.csv`. О качестве данных ничего не известно. Поэтому перед проверкой гипотез понадобится обзор данных. 

На этапе предобработки необходимо будет определить и обработать пропуски и привести данные в столбцах к нужным типам.

На этапе дополнения таблицы необходимо посчитать цену квадратного метра, дату публикации объявления, этаж квартиры (первый, последний, другой), соотношение жилой и общей площади, а также отношение площади кухни к общей площади.
