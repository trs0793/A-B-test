# A-B-test (English)
### 1) Goal and Task Statement:

During the testing of a hypothesis, a new payment mechanism was proposed to the target group on the website, while the control group continued to use the basic mechanism. **My task was to analyze the experiment results and draw conclusions about implementing the new payment mechanism for all users**. The null hypothesis (H0): There is no difference in the average amount between the test and control groups. Alternative hypothesis (H1): There is a difference in the average amount between the test and control groups.

### 2) Tools Used in Project Execution:
- Python (libraries: Pandas, Numpy, Seaborn, Matplotlib, Scipy.stats, Pingouin, Bootstrap)
- Google API

### 3) Results:

Since the metric is a quantitative variable and we have two groups that we plan to compare based on one criterion, and the distribution is non-normal with a small sample size, we used BOOTSTRAP for comparison.
Confidence intervals of parameters for the two groups overlap, so we accept the null hypothesis that there is no difference in the average amount between the test and control groups.

**Therefore, it is proven that implementing the new payment mechanism for all users is NOT recommended!**

# A-B-test (Rusian)
### 1)Цель и условие задачи:

 В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. **Мне необходимо было проанализировать итоги эксперимента и сделать вывод о запуске новой механики оплаты на всех пользователях**. Нулевая гипотеза (H0): Разницы между средней суммой в тестовой и контрольной группе нет. Альтернативная гипотеза (H1): Разница между средней суммой  в тестовой и контрольной группе есть.

 ### 2)Во время выполнения проекта я применял следующе инструменты:
 - Python (библиотеки Pandas, Numpy, Seaborn, Matplotlib, Scipy.stats, Pingouin, Bootstrap);
 - API Google

 ### 3)Результат:
   
 Так как метрика является колличественной переменной и у нас есть 2 группы которые планируем сравнивать по одному критерию, 
и распределение у нас ненормальное и колличество экспериментов мало, то  для сравнения используем BOOTSTRAP
Доверительные интервалы параметров двух групп перекрываются, поэтому мы принимаем нулевую гипотезу,
что разница между средней суммой  в тестовой и контрольной группе нет.

**Поэтому доказанно, что запускать новую механику оплаты на всех пользователей НЕ стоит!**
