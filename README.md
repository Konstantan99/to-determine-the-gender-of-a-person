# to-determine-the-gender-of-a-person

Общая информация
В рамках Sberbank Data Science Journey проходит Data Science Contest. Во время контеста участникам предлагается поработать с банковскими данными и решить несколько исследовательских задач: определить пол клиента по его финансовым тратам в первой задаче, предсказать общий оборот в той или иной категории услуг во второй задаче и предсказать траты каждого клиента в каждой из категорий в третьей. Итоговый рейтинг участника рассчитывается на основе сумме баллов по каждой из задач.

Основные данные представляют из себя историю банковских транзакций, а также демографическую информацию по некоторой выборке клиентов (данные обезличены и специальным образом искажены).

#Задача A
Для клиентов, у которых неизвестен пол (которых нет в обучающей выборке customers_gender_train.csv, но которые есть в transactions.csv), необходимо предсказать вероятность быть мужского пола (значение 1).

Ожидаемый формат посылки решения
customer_id,gender
1111111,0
1111112,1
1111113,0.2
