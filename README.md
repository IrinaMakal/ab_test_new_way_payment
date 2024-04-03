# A/B-тестирование - новая механика оплаты услуг на сайте

<br>В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика.
<br>Необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на всех пользователей.
<br>
<br>Прежде, чем приступить к анализу эффективности внедрения новой механики оплаты услуг на сайте, определяем метрики, по которым будем это оценивать. Решено использовать следующие метрики:
<br>- средний доход на пользователя (ARPU)
<br>- количество платящих пользователей
<br>- средний доход на платящего пользователя (ARPPU)
<br>
<br>Далее проводим предобработку данных, визуализируем полученные результаты, оцениваем их статистическую значимость, делаем выводы.
<br>
<br>**Общий вывод по эсперименту**
<br>Рекомендация по запуску новой механики оплаты услуг на сайте зависит от целевого показателя эксперимента.
<br>Если целевые показатели рост среднего дохода на пользователя (ARPU) и рост количества платящих пользователей, то тест не показал значимого эффекта, а изменения обусловлены другими факторами. А это значит, что лучше оставить действующую (старую) механику оплаты услуг на сайте.
<br>Если же целевой показатель средний доход на платящего пользователя (ARPPU), то тест показал статистически значимые результаты, и мы можем внедрять новую механику оплаты услуг на сайте на всех пользователей.
<br>
<br>**Стек:** pandas, requests, numpy, seaborn, pingouin, matplotlib.pyplot, t-test, тест Манна-Уитни
