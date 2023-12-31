# Портфолио: аналитик данных
## Коротко обо мне
Привет!👋 
<br>
Меня зовут Тимофей, и я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Чем владею
- Инструменты анализа данных: ``SQL``, ``Excel``;
- Системы управления базами данных: ``PostgreSQL``.

## Проекты
### <p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Главной задачей было отредактировать калькулятор юнит-экономики так, чтобы в нём учитывались новоприбывшие студенты в соответствии с планами маркетинга;</li>
  <li>Также было необходимо пересчитать план найма преподавателей с учётом увеличения количества студентов.</li>
</ol>

<p>Основным изменением в калькуляторе было добавление столбца с новыми студентами, однако на случай отклонения от плана был добавлен поправочный коэффициент. После чего был создан динамический расчет количества новых студентов на будущий год, с учетом данного коэффициента. Для перерасчета плана найма преподавателей был построен отдельный калькулятор, в котором динамическими параметрами стали: пропускная способность одного преподавателя и retention преподавателей. Для визуализации изменений для обоих калькуляторов были построены графики.<p>


> <a href="https://docs.google.com/spreadsheets/d/10vkFyyiajg93UCsdSv56FAgPZ0VSPKan0xBX75LfaOY/edit?pli=1#gid=1567542708)">Проект 1</a>


<p>Итоги:<p>
<ol>
  <li>Был создан калькулятор бнит-экономики онлайн школы, который учитавает новых студентов в соответствии с планом маркетинга;</li>
  <li>Создан новый калькулятор, для перерасчета плана найма преподавателей.</li>
</ol>
<br> 

### <p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Построить калькулятор юнит экономики для онлайн кинотеатра;</li>
  <li>Предложить комбинацию параметров для выхода на 25ти процентную маржинальность;</li>
  <li>Построить визуализации.</li>
</ol>

<p>В качестве юнита была выбрана ежемесячная подписка. После чего были в калькулятор были добавлены такие показатели как базовая цена юнита и цена юнита с учетом объёма скидок и fixed косты на юнит. Из данных о подписчиках был получен retention. На основании которого был посчитан lifetime клиента, CAC и CAC на юнит и LTR. После чего был найден оптимальный набор этих параметров для выхода на 25ти процентную маржинальность, а также были построены визуализации юнит-экономик as-is и to-be. В дополнение ко всему, были исследованы данные о поведении пользователей, и построены дополнительные визуализации./<p>

> <a href="https://docs.google.com/spreadsheets/d/1n_HJgCj2n8uQxPivmOcBsxBfiaGqCoHZwKKpVxKPYew/edit#gid=1673848367">Проект 2</a>
 
<p>Итоги:<p>
<ol>
  <li>Создан калькулятор юнит-экономики для онлайн кинотеатра, и найдены оптимальные параметры для выхода на плановую маржинальность;</li>
  <li>Созданы визуализации для юнит-экономики и типового поведения пользователей.</li>
</ol>
<br> 

### <p>Проект 3: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Собрать данные по балансам студентов и просмотреть топ-1000 строк на наличие отклонений в данных;</li>
  <li>Создать визуализацию для отображения и проанализировать полученные графики.</li>
</ol>

<p>С помощью нескольких CTE-запросов для каждого студента был найден день первой успешной транзакции, после чего каждый день проверялось изменение баланса до конца года, и с помощью оконных функций вычислялось куммулятивное изменение баланса, что позволило, получить данные о балансе любого студента в конкретный день. После чего, данные были загружены в Excel и отсортированы по различным признакам.<p>

> <a href="https://github.com/Deensi/portfolio/tree/main/Project_3">Проект 3</a>
 
 <p>Итоги:<p>
<ol>
  <li>В ходе анализа было обнаружено, что студентов баланс уроков студентов в некоторых случаях становиться отрицательным, в следствие чего была выдвинута гипотеза о том, что в БД есть некорректные данные, или же некотрые данные отсутствуют;</li>
  <li>После анализа данных было выявлено несколько закономерностей, с которыми можно ознакомиться, посмотрев файл Project_3.xlsx лист "Задание 2".</li>
</ol>

## Контактная информация
- Email: denisovts@mail.ru
- Telegram: t.me/IMIXEDI
