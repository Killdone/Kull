**Задача:**

Выявить для магазина закономерности, определяющие успешность игры. Это позволит владельцам закупить актуальный товар на следующий год и спланировать рекламную кампанию. 
***

**Стек**

В наличие данные о продаже игр в мире данные до 2016 года

- Name — название игры

- Platform — платформа

- Year_of_Release — год выпуска

- Genre — жанр игры

- NA_sales — продажи в Северной Америке (миллионы проданных копий)

- EU_sales — продажи в Европе (миллионы проданных копий)

- JP_sales — продажи в Японии (миллионы проданных копий)

- Other_sales — продажи в других странах (миллионы проданных копий)

- Critic_Score — оценка критиков (максимум 100)

- User_Score — оценка пользователей (максимум 10)

- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.
***
**Инструменты:**

В этом проекте я использовал библиотеки seaborn, numpy, math, scipy, matplotlib и pandas. Применял исследовательский анализ и двухстороние гипотезы. 
***
**Результат:**

1. Первым делом я предобробатывал таблицу: устранял в ней пропуски, дубликаты и мусор, чтобы данные были максимально пригодными для последующего анализа.

2. Затем я посчитал суммарные продажи по всем регионам и записал их в новый столбец, эти данные мне будут нужны для дальнейшего исследовательского анализа.

3. Из исследовательского анализа я узнал, как менялись продажи по платформам за несколько десятков лет, и как часто меняются поколения консолей. Также узнал, какие консоли берут верх в рахзных регионах, дабы сделать на них ставку в будущем году. Провел исследование в области жанров, чтобы определить на сколько они популярны и сколько денег приносят.

4. Определил популярные платформы и жанры для пользователей каждого региона. 

5. Проверил нулевую и альтернативную гипотезу для зависимости продаж от рейтингов критиков. 
***
**Статус проекта:**

 Завершен

