# Техники тест-дизайна


Во время обучения были изучены различные техники тест-дизайна и отработаны на практике на примере интернет-магазина.
<ul>
<li>Тестирование формы регистрации с помощью анализа граничных значений</li>
<p><p>
 <b>Задание</b>:
  на основе требований заполнить таблицу тестовыми данными с использованияем граничных значений и классов эквивалентности.
  Требования: 
    Имя пользователя должно содержать от 3 до 15 символов и может включать буквы, цифры и символы: _.
    Пароль должен содержать не менее 8 символов, включая минимум одну букву и одну цифру.
  </p>

[Таблица с решением](https://docs.google.com/spreadsheets/d/1oJyM79mI5pPRDFae0a2N3YfnsU3tb3JIbq-wwOzsQ8I/edit?usp=sharing)
<p>
<p>
  <p>
<li>Тестирование фильтрации и сортировки с помощью попарного тестирования</li>
<p><p>
  <b>Задание</b>:
  на основе требований заполнить таблицу тестовыми данными используя попарное тестирование.
  Требования: 
    Покупатель может указать диапазон цен, выбрать категорию, производителя и опцию бесплатной доставки для фильтрации списка товаров.
    Покупатель может выбрать сортировку товаров по имени (от А до Я и от Я до А) и по цене (от низкой к высокой и от высокой к низкой).
  </p>
  <p>

[Таблица с исходными данными и тестируемыми значениями](https://docs.google.com/spreadsheets/d/1AMGfgESWQQi8MpbDOQcw-qi_hoEM-azFapjJ4YUzYzk/edit?usp=sharing)
<p> Работа выполнялась с помощью "Теремка", генерировала тестовые данные для тестирования на основе алгоритма Pairwise.
<p>
<p>
  <p>
<li>Тестирование модуля оплаты Paypal с помощью Таблицы принятия решений</li>
<p><p>
  <b>Задание</b>:  
    на основе следующей информации создать таблицу принятия решений.
  В исследуемом приложении есть модуль, включающий оплату через Paypal.
  У аккаунта Paypal есть три статуса: valid, invalid и blocked, а также такая характеристика, как доступный баланс, который может быть нулевым и положительным.
  В случае, если статус карты valid, а баланс на аккаунте достаточный для покупки, пользователь может совершить покупку. Во всех остальных случаях транзакция будет отклонена.
  </p>

[Таблица с решением](https://docs.google.com/spreadsheets/d/18CbhO6aIOTZIdYZTqhxBw1SAW9a_F5-cwDL-7L-NsVY/edit?gid=0#gid=0)
</ul>
