# Анализ рынка кинопроката
Заказчик этого исследования — Министерство культуры Российской Федерации. Нужно изучить рынок российского кинопроката и выявить текущие тренды.  

- Работать будем с данными, опубликованными на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск. 

- Цель исследования - изучить рынок российского кинопроката и выявить текущие тренды. Определить интерес зрителя к фильмам, получившим гос. поддержку.

- Работать будем с данными, опубликованными на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

- План работы: Шаг 1. Открыть файлы с данными и объедините их в один датафрейм. Шаг 2. Предобработка данных. Шаг 3. Провести исследовательский анализ данных. Шаг 4. Исследовать фильмы, которые получили государственную поддержку. Шаг 5. Написать общий вывод.

  #ВЫВОД

  В датасете есть дубликаты по названию фильма, но у этих кинокартин разные номера прокатных удостоверений, поэтому оставили данные без доп. обработки; Также есть фильмы с одинаковыми номерами прокатных удостоверений, но, проверив, такие фильмы на официальном - подтвердили, что все так и есть. Видимо, под одним номером может быть в прокате несколько фильмов. В бюджете фильмов были нулевые значения. В таких строках нулевой бюджет заменили на сумму поддержки. Для анализа добавили дополнительные столбцы с годом старта показа картины, первого в списке режиссера, и первого в списке жанра, а также отношение суммы поддержки к бюджету. Больше всего фильмов было показано в кинотеатре в 2019 году, чуть меньше - в 2016. Минимальная сумма сборов была в 2015, максимальная в 2018. Наибольшая "средняя" сумма сборов приходится на 2017 год. Больше всего сборов у фильмов 16+. Если смотреть по годам, то в 2017 году кино 16+ принесло больше всех денег, но в 2015 более "кассовое" кино было 12+. Больше всего было денег выделено гос. фондом в 2019 году, чуть меньше - в 2016. Но в среднем по медиане самый большой бюджет на каждый фильм приходится на 2018 год. Самые худшие (по рейтингу) фильмы были в прокате в 2016 году. В остальные годы средняя оценка была около 6 баллов. На рейтинг фильма увеличение суммы поддержки особо не влияет. Несмотря на убыточность более 75% фильмов в данной выборке, за счет хитов киноиндустрия окупается. Больше всего фильмов с суммой поддержки до 100 млн рублей, такие фильмы, в основном, с рейтингом чуть больше 6 балов. При этом нет плохих фильмов (с оценкой ниже 5 балов) с суммой поддержки больше 200 млн рублей. По количеству и по сумме поддержки на первом месте жанр "драма", на втором "комедия". Самую большую сумму поддержки получил Федор Бондарчук.
