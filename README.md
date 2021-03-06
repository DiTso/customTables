customTables
============

### customTables - решение для хранения ресурсов MODxEvo в отдельных пользовательских таблицах
 ---------
Используются разработки из:
 - MODxAPI - https://github.com/AgelxNash/resourse
 - DocLister - https://github.com/AgelxNash/DocLister
 - CResource - https://github.com/AgelxNash/CResource
 
 ### Что вы получаете (немного скриншотов)
 *1. список товаров (дочерние ресурсы папки "товары") - https://yadi.sk/i/GmvXCpWY3UKwJK<br>
 *2. тот же список, но отфильтрован по категории товара, продавцу и диапазону цен, с сортировкой по возрастанию цены - https://yadi.sk/i/QMyNXfZw3UKwY9<br>
 *3. выборки товаров по tagSaver - товары конкретного продавца- https://yadi.sk/i/WjkP2dkG3UKwer и товары конкретной категории - https://yadi.sk/i/t-FspIQh3UKwp4<br>
 *4. список туров из пользовательской таблицы (не из дерева) с аналогичным функционалом сортировки/фильтрации https://yadi.sk/i/yI1g-Yyo3UKvVH<br>
 *5. редактирование туров из пользовательской таблицы (идентично редактированию ресурса, вы просто создаете обычный TV-параметр и прикрепляете его к нужному шаблону) - https://yadi.sk/i/tWmFrtWL3UKx4n и еще более интересное https://yadi.sk/i/yw1Wx_vJ3UKxAW<br>


 ### Возможности
 ---------
* 1. Создание, редактирование, удаление и вывод дочерних ресурсов из стандартной таблицы modx_site_content. Фильтрация по любым параметрам (как из таблицы site_content, так и по TV), сортировка по столбцам - https://yadi.sk/i/yI1g-Yyo3UKvVH
* 2. Создание, редактирование, удаление и вывод дочерних ресурсов из стандартной таблицы modx_site_content с использованием тегов tagSaver. Фильтрация по любым параметрам (как из таблицы site_content, так и по TV), сортировка по столбцам
* 3. Создание и вывод в админку и на сайт ресурсов из пользовательских таблиц
* 4. Удобное добавление и редактирование ресурсов из пользовательских таблиц средствами и формами MODx, возможности поиска по заданным в конфигурации полям. Т.е. все выглядит идентично редактированию обычного ресурса MODx со всеми прикрепленными к данному шаблону TV -параметрами
* 5. Использование TV-параметров в "штатном режиме" через прикрепление их к шаблонам, которые затем заносятся в пользовательскую таблицу
* 6. Контроллер customtables для DocLister для вывода списков из пользовательских таблиц
* 7. Фильтр ct_filter для котроллера customtables
* 8. Класс modCustomTables для работы с пользовательскими таблицами средствами MODxAPI
* 9. Доработаны плагин и сниппет route под цели решения

