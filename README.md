# Дорогой посетитель, категорически приветствую тебя в моей скромной обители! #Hello world
***Меня зовут Стерхов Александр и я люблю рыться в данных! Guilty pleasure, так сказать, или не guilty:)***

Так, КХМ-КХМ, дубль два. Как я выше проговорился зовут меня Александром, явлюсь я без пяти минут(1,5 месяцев) выпускником факультета Data Science Яндекс.Практикума. Ниже представленны визуализация моих вечеров, дней, а иногда и утрр в формате кода за последних 7 месяцев моей жизни/обучения в Практикуме.
Проекты расположены в хронологическом порядке, от первого проекта по базовому питону выполненного в феврале этого года до последнего проекта по компьютерному зрению, который будет готов к концу августа этого же года. 

***Описание выполнено в формате: ***

        -Тема проекта, 
        
        -Модуль, теоретические знания которого закреплялись в данном проекте
        
        -Основные методы, которые отрабатывались на практике в данном проекте
        
        -Описание проекта
        
Все требуемые для выполнения проекта библиотеки старался располагать в первом сообщении кодового формата тетрадки, обзор и описание датасета ячейкой ниже. Если где-то не так, то это не иначе как происки недоброжелателей!.. а не я виноват, разумеется.


***Собственно сами проекты:***
       
## 1. Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов
*Проект по модулю "Базовый python"*

***Используемые навыки:*** Pandas - дубликаты, пропуски, логическая индексация, группировка, сортировка.

На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.
Сравнение Москвы и Петербурга окружено мифами:
- Москва — мегаполис, подчинённый жёсткому ритму рабочей недели;
- Петербург — город своеобразной культуры, непохожий на Москву.
Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки мы проверим данные и сравним поведение пользователей двух столиц.

        
## 2. Исследование надёжности заёмщиков — анализ банковских данных
*Проект по модулю "Предобработка данных"*

***Используемые навыки:*** Pandas, Предобработка данных(дубликаты, пропуски, категоризация, декомпозиция), groupby, def, apply.
        
На основе статистики о платёжеспособности клиентов нам предстоит исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок. На основе данных кредитного отдела банка исследовать влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.
    
    
## 3. Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости
*Проект по модулю "Исследовательский анализ данных"*

***Используемые навыки:*** Matplotlib, NumPy, Pandas, исследовательский анализ данных, предобработка данных, категоризация, histogram, boxplot, scattermatrix, scatterplot.

Используя данные сервиса Яндекс.Недвижимость, определим рыночную стоимость объектов недвижимости и типичные параметры квартир. На основе данных сервиса Яндекс.Недвижимость определим рыночную стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведем предобработку данных. Добавим новые данные.
        
        
## 4. Определение выгодного тарифа для телеком компании
*Проект по модулю "Статистический анализ данных"*

***Используемые навыки:*** Статистический анализ данных, Matplotlib, NumPy, Pandas, Python, SciPy, histogram, boxplot, статистический тест, критерий Стьюдента, проверка статистических гипотез.
        
На основе данных клиентов оператора сотовой связи проанализируем поведение клиентов и поиск оптимального тарифа. Проведем предварительный анализ использования тарифов на выборке клиентов, проанализируем поведение клиентов при использовании услуг оператора и рекомендуем оптимальные наборы услуг для пользователей. Проведем предобработка данных, их анализ. Проверем гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.
    

## 5. Анализ факторов определяющих успешность игры
*Проект по модулю "Сборный проект №1"*

***Используемые навыки:*** Много агрегаций с query и pivot_table, графиков в plotly.express, анализа данных, а так же scipy.stats,
    
Определение токсичности комментариев. Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
    
    
## 6. Классификаиция клиентов телеком компании
*Проект по модулю "Введение в МО"*

***Используемые навыки:*** train_test_split, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, mean_squared_error, accuracy_score, plotly.express, pyplot, Matplotlib, Pandas, Scikit-learn.
        
На основе данных предложить клиенту тариф. Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тарифов.
    
    
## 7. Прогнозирование оттока клиента Банка
*Проект по модулю "Обучение с учителем"*

***Используемые навыки:*** Matplotlib, Pandas, Scikit-learn, train_test_split, train_test_split, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, f1_score, roc_auc_score, shuffle, StandardScaler, GridSearchCV, RandomizedSearchCV.
    
На основе данных из банка определить клиентов, которые могут уйти. Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.


## 8. Определение наиболее выгодного региона нефтедобычи
*Проект по модулю "Машинное обучение в бизнесе"*

***Используемые навыки:*** Подсчет прибыли и рисков, enumerate, mean_squared_error, LinearRegression, train_test_split, Pandas, Scikit-learn, доверительный интервал, бутстреп.
    
На основе данных геологи разведки выбрать район добычи нефти. Нам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Строим модель для определения региона, где добыча принесёт наибольшую прибыль.


## 9. Исследование технологического процесса очистки золота
*Проект по модулю "Второй сборный проект"*

***Используемые навыки:***  Исследовательский анализ данных, plotly.express, DummyRegressor, DecisionTreeRegressor, RandomForestRegressor, StandardScaler, GridSearchCV, RandomizedSearchCV, make_scorer, seaborn, mean_absolute_error, Matplotlib, NumPy, Pandas, Python, Scikit-learn.
    
Спрогнозировать концентрацию золота при проведении процесса очистки золота. Строитстся модель машинного обучения для промышленно компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


## 10. Защита данных клиентов страховой компании
*Проект по модулю "Линейная алгебра"*

***Используемые навыки:*** Линейная алгебра, r2_score, np.dot(), LinearRegression, Scikit-learn.
    
Разработка модели анонимизации персональных данных. Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.


## 11. Построение модели определения стоимости автомобиля
*Проект по модулю "Численные методы"*

***Используемые навыки:*** OrdinalEncoder, StandardScaler ,numpy ,mean_squared_error ,RandomForestRegressor, RandomizedSearchCV ,Catboost, LGBMRegressorv.
    
Разработка системы рекомендации стоимости автомобиля на основе его описания. Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных необходимо построить модель для определения стоимости автомобиля.


## 12. Прогнозирование количества заказов такси на следующий час
*Проект по модулю "Временные ряды"*

***Используемые навыки:*** Декомпозиция временного ряда, анализ, тест Дикки-Фуллера, генерация фич, ресэмплинг, LinearRegression, Pandas, Python, Scikit-learn, statsmodels.
    
Разработка системы предсказания объема заказов. Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.


## 13. Обучение модели классификации комментариев
*Проект по модулю "МО для текстов"*

***Используемые навыки:*** WordNetLemmatizer, BERT, Pandas, Python, nltk, tf-idf, Catboost, LogisticRegression, RandomizedSearchCV.
    
Определение токсичности комментариев. Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.


## 14. Обработка фотографий покупателя	(не завершен)
*Проект по модулю "Компьютерное зрение"*

***Используемые навыки:*** .

Определение возраста по фотографии. Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.

        
