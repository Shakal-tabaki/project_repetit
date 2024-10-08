<h1> Построение ML-продукта для выявления и оптимизации платежей преподавателей сервиса Repetit.ru</h1>


<h1 align="left">Описание:</h1>

Сервис передает контакты клиента (ученика) репетитору. Если репетитор начинает заниматься с учеником, то он должен платить сервису комиссию от каждого занятия. Но в реальности так происходит не всегда. Иногда, это из-за того, что репетитор звонит по телефону и ему просто не отвечают. Некоторые репетиторы плохо договариваются о занятиях или обманывают. Сервис теряет деньги каждый раз, когда отдаёт заявку неэффективному репетитору. Заказчику нужно как можно раньше понять, что репетитор недобросовестный или мошенник, чтобы отключить его от сервиса и отдавать заявки ответственным репетиторам.
Сейчас эта задача решается ручным просмотром сотрудниками или никак.

__Описание задачи:__


<h>Разработать модель, которая по имеющейся информации о репетиторе и проведенных им занятий будет классифицировать репетиторов на платящих и неэффективных. Оценка качества модели будет производиться с использованием метрики F1.</h>

__Данные__:

Данные можно получить из яндекс диска 
'https://disk.yandex.ru/d/ZE6bSWd4M5P0Ew':
* `teacher_info.feather` — информация о репетиторах;
* `teachers.feather` — статистика по репетиторам, содержит таргет;
* `lesson_course.feather` — данные об ученике;
* `lessons.feather` — данные о занятиях;
* `teacher_prices.feather` — цены на занятия репетиторов;
* `orders.feather` — данные о заявках;

__Файлы__  

* `repetit_pro.ipynb` - Основной файл с отчетом.  
* `ТЗ Репетит (Задача по преподавателям).docx` - ТЗ предоставленное заказчиком.   
* `all_data.csv` - Датафрейм созданный в процессе работы для обьединения   предоставленных данных.  


__Статус проекта:__

Проект закончен. Данные были подготовленны к обучению модели. Модель достигна достаточного порога значение решающей метрики `F1`.


<h1 style="color:#539394">Инструменты:</h1>

<span style="color:#539394">  

- python 3.11.4  
- pandas 1.5.3  
- numpy 1.23.5 
- sklearn 1.3.0  
- matplotlib 3.7.2  
- seaborn 0.12.2  
- CatBoost 1.2   
- LgbmBoost 4.1.0  
- XGBoost 1.7.6 

</span>   
