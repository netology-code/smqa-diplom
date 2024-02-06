# Итоговая работа по ручному тестированию мобильных приложений


### Цель итоговой работы

Задания итоговой работы помогут закрепить на практике полученные знания по ручному тестированию мобильных приложений. Цели итоговой работы - погрузиться в процессы, которые ожидают вас при устройстве на работу, потренироваться в выполнении рабочих задач, составить представление о базовых обязательных проверках в мобильном тестировании.

В процессе работы над заданиями вы:

- поработаете с документацией;
- опишите баг-репорты на найденные баги;
- попрактикуетесь с основным функционалом сниффера Charles;
- протестируете работу диплинков.

В результате выполнения итоговой работы вы:

- научитесь применять функции сниффера для рабочих задач;
- получите понимание и научитесь тестировать функционал диплинков;
- закрепите навыки заведения  баг-репортов;
- потренируетесь в составлении чек-листов c минимальными требованиям.


------

### Инструкция к заданию

1. Сделайте копию [Шаблона для курсовой работы](https://docs.google.com/spreadsheets/d/1cq1zeOXVzf2cT2ZdXyf2HQ58DJ9euU98rvVG4kBNALY/edit#gid=0) и сохраните себе на Google Disk. Этот документ будет вашим решением итоговой работы, ссылку на который вы прикрепите в личном кабинете.
3. В названии файла укажите свои фамилию, имя и группу вместо Name, Surname, Group.
4. Внутри документа есть ссылки на шаблоны для выполнения отдельных заданий. Эти шаблоны тоже скопируйте себе на Google Disk.
5. Зайдите в “Настройки доступа” всех своих шаблонов и выберите доступ “Просматривать могут все в Интернете, у кого есть ссылка”.  Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
6. Перед отправкой своего решения обязательно отформатируйте свои таблицы с переносами и правильной вёрсткой, иначе они будут возвращены на доработку ([ссылка на пример оформления](https://docs.google.com/document/d/1yDj9YWZ6wF7v8edq_aJkSFR9g7QgUil5yuuZgbHDzvE/edit)).
   


------


### Задание 1. Составление чек-листа 

Перед вами [макет экрана iOS-приложения в Figma](https://www.figma.com/file/P91pWCXiUw1vzXdHHVzQ6i/Untitled?type=design&node-id=0-1&mode=design).  Детальных требований и прочей информации о функционале у вас нет.  Известно только, что все данные на экране появляются постепенно по ходу ответа пользователя чат-боту в режиме диалога. 

Ваша задача – оценить функционал экрана по макету и составить необходимый список проверок в виде чек-листа. 

#### Требования к выполнению

- Чек-лист должен представлять собой структурированный список, который содержит набор функциональных позитивных и негативных проверок тестируемого экрана. Можно выделить для удобства блоки проверок. 

- Каждый пункт проверки  должен быть в отдельной ячейке списка и со своим приоритетом. 

- При составлении списка проверок должны учитываться различные варианты состояния экрана.  Помните, что это мобильное приложение, и важно не забывать применять best practice с учетом особенностей тестирования iOS-приложений. Например, как повлияет смена размера шрифта на отображение чата? Что будет, если свернуть и развернуть экран с введенными данными? Что ожидается при свайпе экрана вправо/влево и т.п?

<details close>
  <summary>Кратко о Figma </summary>

Это инструмент для дизайна интерфейсов и прототипирования, который стал очень популярным среди дизайнеров и бизнес-аналитиков, разработки.  Функционал Figma позволяет создавать и редактировать макеты пользовательских интерфейсов, работать с векторами, прототипировать и делиться проектами с командой. 

Легкая интеграция с процессами разработки дает возможность экспорта макетов в различные форматы, что позволяет легко совмещать дизайн с разработкой под разные платформы.
Коллаборация в реальном времени  позволяет работать одновременно с членами команды, видеть изменения в режиме реального времени и оставлять комментарии. Все файлы макетов сохраняются в облаке, что обеспечивает доступ к проектам из любой точки мира и на любом устройстве.

 
</details>


------

### Задание 2. Составление баг-репортов

Перед вами  [скриншоты приложений](https://drive.google.com/drive/u/1/folders/19g7M-dr0rjYaBWZx409g3xMbpfMm__8j) с ошибками.   
Оцените их,  проанализируйте, что не так. Обратите внимание на состояние статус бара девайса на некоторых из них  и составьте минимум 5 баг-репортов на любые из предоставленных скриншотов.



#### Требования к выполнению

1. Результат опишите в предложенном [шаблоне заведения баг-репортов](https://docs.google.com/spreadsheets/d/1pog6M08wbhM-OzdWgQGDP14tn7ZVjEMLHq2bQTwEV2g/edit#gid=0) или оформите в личном проекте в Jira, приложив ссылку на документ со скриншотами заведенных ошибок.

2. При выполнении в Jira укажите обязательные параметры баг-репортов (тестовое окружение, приоритет и серьезность,шаги, результаты).

3. Постарайтесь найти максимум ошибок, развивайте насмотренность. Обратите внимание, что на один скриншот можно составить один и более баг-репорт. 

4. В названиях баг-репортов указывайте названия скриншотов, в которых возникают ошибки.

5. В тестовом окружении  можно описать то устройство, с которого проводилась бы проверка (ваше актуальное устройство), номер сборки укажите условный 5.0.12.

-----


### Задание 3. Тестирование диплинка

Вам на тестирование отдали [диплинк](https://inlnk.ru/golGMO), который планируется использовать в email рассылке и распространять в рекламе соцсетей.

Напишите список сценариев тестирования работы диплинка на мобильном девайсе. Опирайтесь на основные пользовательские юзкейсы.  


<details close>
  <summary> Что такое Deeplink (диплинк)? </summary>
Deeplink (или диплинк) — это гиперссылка, которая перенаправляет пользователя в конкретный раздел приложения или сайта. Данная функция сокращает количество промежуточных действий пользователя и помогает ему попасть на нужную страницу за минимальное количество кликов. Ссылка должна вести себя по-разному для пользователей, у которых приложение уже установлено, и для пользователей, у которых оно еще не установлено.

Как чаще всего используются диплинки:

1. Рекламные кампании для привлечения новых пользователей и отслеживание, откуда идет трафик установок приложения.
2. Перевод пользователей с веб-лендингов  в мобильные приложения.
3. Перенаправление из электронных писем,сообщений в мессенджерах в приложение на нужный раздел, товар, оффер.
   
</details>

-----

### Задание 4. Работа с Charles Proxy

#### 4.1

Вы получили  тестовый apk файл приложения «Взахлеб», которое необходимо протестировать на разные сценарии. 

1. Скачайте [файл apk](https://drive.google.com/file/d/1VSx1zk6QKMOh1H9EHUDgubJhY76dZ7Co/view) (при попытке скачать файл могут отображаться оповещения от браузера о небезопасном скачивании, так как вы устанавливаете его не из официального магазина приложения, но сам по себе файл безопасен).

2. Подготовьте Android девайс и настроенный снифер Charles Proxy (подробно разбиралось на лекции «Cнифферинг»). 

3. Изучите запросы приложения, их работу. Проверьте заголовки запросов и ответы.
Все запросы приложения вы найдете по адресу `https://api.zahleb.me`.  

4. Откройте любую понравившуюся книгу и найдите в ответе книги параметр, который отвечает за количество просмотров книги.

![Скрин 1](https://github.com/netology-code/smqa-diplom/assets/77622076/079bd2d4-b54c-445f-883f-4eefd1b0f5fb)

5. Протестируйте на клиенте вёрстку и проверьте, как отобразится большое количество просмотров, если книга будет очень популярной. Доступа к  Базе данных, где вы можете изменить количество, нет. Зато есть Charles :) 

6. Измените параметр в ответе сервера. Для этого используйте функцию `Rewrite` или `Break points`. 

В качестве решения предоставьте:
- скриншот настроек используемой функции Charles,
- скриншот экрана приложения с измененным количеством просмотров в выбранной книге. 

<details close>
  <summary> Для чего используется сниффер </summary>
   
В мобильном тестировании сниффер используется на постоянной основе. Возможность просмотра трафика с  устройств значительно облегчает работу тестировщика клиент-серверных мобильных приложений.

Несколько примеров рядовых рабочих задач, где вам всегда пригодится сниффер:
- достать токен авторизации с мобильного устройства,  
- посмотреть код ответа запроса,  
- получить тело ответа, при каком-то действии на мобильном устройстве,  
- выбрать запрос, поменять  символ в  токене авторизации и проверить, будет ли ошибка 401, 
- вызвать ошибку тайм-аута на экране,
- выбрать запрос, поменять ему метод POST на PUT и проверить, будет ли ошибка 405,
- заменить url.   

</details>

#### 4.2* (необязательное к выполнению)

Найдите запрос, отвечающий за получение конфига управления функционалом приложения `https://api.zahleb.me/parse/config`.    
Это главный конфигурационный файл приложения. В нем удаленно задаются различные  параметры, например:
- поддерживаемые языки,   
- запуск АБ-теста для конкретного пользователя,
- получение бонусов за реферальные приглашения и тп.
  
В качестве решения укажите параметр  `debugSettingsPassword`, найденный в конфиге.


-----

### Правила приема работы

В личном кабинете отправлены:

- ссылка на Google Doc с выполненными заданиями;
- в документе настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка»;
- решение оформлено по [шаблону](https://docs.google.com/spreadsheets/d/1cq1zeOXVzf2cT2ZdXyf2HQ58DJ9euU98rvVG4kBNALY/edit#gid=0);
- таблицы в решении отформатированы с переносами и правильной вёрсткой ([ссылка на пример оформления](https://docs.google.com/document/d/1yDj9YWZ6wF7v8edq_aJkSFR9g7QgUil5yuuZgbHDzvE/edit)).
   
------

### Критерии оценки

Для получения зачёта:  
- выполнены все обязательные задания в соответствии с прописанными требованиями,
- приложены соответствующие скриншоты и файлы,
- решение оформлено по [шаблону](https://docs.google.com/spreadsheets/d/1cq1zeOXVzf2cT2ZdXyf2HQ58DJ9euU98rvVG4kBNALY/edit#gid=0),
- все таблицы отформатированы с переносами и правильной вёрсткой.
  

