# Прогнозирование цен на автомобили

## Описание проекта
На основании исторических данных необходимо разработать модель предсказывающую цены на автомобили
## Описание данных
**Признаки**
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- NotRepaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя
**Целевой признак**
Price — цена (евро)
## Задача
Предсказать цену на автомобили
## Используемые библиотеки
*pandas* *numpy* *matplotlib* *seaborn* *sklearn* *lightgbm* *catboost*
## Используемые модели
*LinearRegression* *RandomForestRegressor* *DecisionTreeRegressor* *CatBoostRegressor* *lightgbm*



