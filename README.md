Комплексная автоматизация

|Функция, метод|Расположение|Описание|
|----|-|-| 
|Функция ВыполнитьЗапрос(Знач HTTPЗапрос, Знач ИмяХоста)|о.м.GoogleПереводчик||
|Функция НастройкиАвторизации() Экспорт|о.м.GoogleПереводчик||
|Функция ЗначениеВJSON(Значение) |о.м.GoogleПереводчик||
|Функция JSONВЗначение(Строка,ИменаСвойствСоЗначениямиДата=Неопределено|о.м.GoogleПереводчик||
|Процедура ЗаписатьОшибкуВЖурналРегистрации(Комментарий)|о.м.GoogleПереводчик||
|Процедура СообщитьПользователю(Знач ТекстСообщения,Знач КлючДанных=Неопределено,Знач Поле = "",|о.м.ОбщегоНазначения|Формирует и выводит сообщение, которое может быть связано с элементом управления формы|
|Функция ЗначенияРеквизитовОбъекта|о.м.ОбщегоНазначения|Возвращает структуру, содержащую значения реквизитов, прочитанные из информационной базы по ссылке на объект|
|Функция ЗначениеРеквизитаОбъекта|о.м.ОбщегоНазначения|Возвращает значения реквизита, прочитанного из информационной базы по ссылке на объект|
|Функция ЗначенияРеквизитовОбъектов|о.м.ОбщегоНазначения|Возвращает значения реквизитов, прочитанные из информационной базы для нескольких объектов|
|Функция ЗначениеРеквизитаОбъектов|о.м.ОбщегоНазначения|Возвращает значения реквизита, прочитанного из информационной базы для нескольких объектов|
|Процедура УстановитьЗначениеРеквизита|о.м.ОбщегоНазначения|Добавляет или изменяет значение реквизита в объекте|
|Процедура УстановитьЗначенияРеквизитов|о.м.ОбщегоНазначения|Добавляет или изменяет значения реквизитов в объекте|
|Функция ПредопределенныйЭлемент|о.м.ОбщегоНазначения|Возвращает ссылку предопределенного элемента по его полному имени|
|Функция ПроверитьПроведенностьДокументов|о.м.ОбщегоНазначения|Проверяет статус проведения переданных документов и возвращает те из них, которые не проведены|
|Функция ПровестиДокументы(Документы)|о.м.ОбщегоНазначения|Выполняет попытку проведения документов|
|Функция ЕстьСсылкиНаОбъект|о.м.ОбщегоНазначения|Проверяет наличие ссылок на объект в базе данных|
|Функция ЗаменитьСсылки|о.м.ОбщегоНазначения|Производит замену ссылок во всех данных. После замены неиспользуемые ссылки опционально удаляются|
|Функция ПодчиненныеОбъекты()|о.м.ОбщегоНазначения|Возвращает связи подчиненных объектов и перечень реквизитов, по которым осуществляется связь|
|Функция ЭтоМобильныйКлиент()|о.м.ОбщегоНазначения|Возвращает Истина, если клиентское приложение является мобильным клиентом|
|Функция ПредставлениеЛокальнойДатыСоСмещением(ЛокальнаяДата)|о.м.ОбщегоНазначения|Преобразует локальную дату к формату "YYYY-MM-DDThh:mm:ssTZD" согласно ISO 8601|
|Функция ИнтервалВремениСтрокой(ВремяНачала, ВремяОкончания = Неопределено)|о.м.ОбщегоНазначения|Возвращает строковое представление интервала между переданными датами или относительно переданной даты и текущей даты сеанса|
|Функция ИмяЗначенияПеречисления(Значение)|о.м.ОбщегоНазначения|Возвращает строковое имя значения перечисления по его ссылке|
|Функция ТаблицаЗначенийВМассив(ТаблицаЗначений)|о.м.ОбщегоНазначения|Преобразует таблицу значений в массив структур|
|Функция СтрокаТаблицыЗначенийВСтруктуру(СтрокаТаблицыЗначений)|о.м.ОбщегоНазначения|Преобразует строку таблицы значений в структуру|
|Функция СтруктураПоМенеджеруЗаписи(МенеджерЗаписи, МетаданныеРегистра)|о.м.ОбщегоНазначения|Создает структуру, содержащую имена и значения измерений, ресурсов и реквизитов переданного менеджера записи регистра сведений|
|Функция ВыгрузитьКолонку(КоллекцияСтрок, ИмяКолонки, ТолькоУникальныеЗначения = Ложь)|о.м.ОбщегоНазначения|Создает массив и копирует в него значения, содержащиеся в колонке объекта, для которого доступен обход посредством оператора Для каждого … Из|
|Функция КоллекцииИдентичны|о.м.ОбщегоНазначения|Сравнивает две коллекции строк (ТаблицаЗначений, ДеревоЗначений и т.д.)|
|Функция ДанныеСовпадают(Данные1, Данные2)|о.м.ОбщегоНазначения|Сравнивает данные сложной структуры с учетом вложенности|
|Функция ФиксированныеДанные(Данные, ВызыватьИсключение = Истина|о.м.ОбщегоНазначения|Преобразует в фиксированный варинт структуры, соответствия,массива|
|Функция СкопироватьРекурсивно(Источник, ФиксироватьДанные = Неопределено)|о.м.ОбщегоНазначения|Создает полную копию структуры, соответствия, массива, списка или таблицы значений, рекурсивно|
|Функция ПредметСтрокой(СсылкаНаПредмет)|о.м.ОбщегоНазначения|Возвращает описание предмета в виде текстовой строки|
|Функция СтруктураСвойствДинамическогоСписка()|о.м.ОбщегоНазначения|Создает структуру для второго параметра СвойстваСписка процедуры УстановитьСвойстваДинамическогоСписка|
|Процедура УстановитьСвойстваДинамическогоСписка(Список, СвойстваСписка)|о.м.ОбщегоНазначения|Установить текст запроса, основную таблицу или динамическое считывание в динамическом списке|
|Функция УстановитьВнешнееСоединениеСБазой(Параметры)|о.м.ОбщегоНазначения|Устанавливает внешнее соединение с информационной базой по переданным параметрам подключения и возвращает указатель на это соединение|
|Функция ЭтоДокумент(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоСправочник(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоПеречисление(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоПланОбмена(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоПланВидовХарактеристик(ОбъектМетаданных|о.м.ОбщегоНазначения||
|Функция ЭтоБизнесПроцесс(ОбъектМетаданных|о.м.ОбщегоНазначения||
|Функция ЭтоЗадача(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоПланСчетов(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоПланВидовРасчета(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоРегистрСведений(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоРегистрНакопления(ОбъектМетаданных|о.м.ОбщегоНазначения||
|Функция ЭтоРегистрБухгалтерии(ОбъектМетаданных|о.м.ОбщегоНазначения||
|Функция ЭтоРегистрРасчета(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоКонстанта(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоРегламентноеЗадание(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоРегистр(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ЭтоОбъектСсылочногоТипа(ОбъектМетаданных)|о.м.ОбщегоНазначения||
|Функция ИменаРеквизитовПоТипу(Ссылка, Тип)|о.м.ОбщегоНазначения|Возвращает имена реквизитов объекта заданного типа|
|Функция ИмяБазовогоТипаПоОбъектуМетаданных(ОбъектМетаданных)|о.м.ОбщегоНазначения|Возвращает имя базового типа по переданному значению объекта метаданных|
|Функция МенеджерОбъектаПоПолномуИмени(ПолноеИмя)|о.м.ОбщегоНазначения|Возвращает менеджер объекта по полному имени объекта метаданных|
|Функция МенеджерОбъектаПоСсылке(Ссылка)|о.м.ОбщегоНазначения|Возвращает менеджер объекта по ссылке на объект|
|Функция ЭтоСсылка(ПроверяемыйТип)|о.м.ОбщегоНазначения|Проверка того, что переданный тип является ссылочным типом данных|
|Функция СсылкаСуществует(ПроверяемаяСсылка)|о.м.ОбщегоНазначения|Проверяет физическое наличие записи в информационной базе данных о переданном значении ссылки|
|Функция ВидОбъектаПоСсылке(Ссылка)|о.м.ОбщегоНазначения|Возвращает имя вида объектов метаданных по ссылке на объект|
|Функция ВидОбъектаПоТипу(ТипОбъекта)|о.м.ОбщегоНазначения|Возвращает имя вида объектов метаданных по типу объекта|
|Функция ИмяТаблицыПоСсылке(Ссылка)|о.м.ОбщегоНазначения|Возвращает полное имя объекта метаданных по переданному значению ссылки|
|Функция ЗначениеСсылочногоТипа(Значение) |о.м.ОбщегоНазначения|Проверяет, что переданное значение имеет ссылочный тип данных|
|Функция ОбъектЯвляетсяГруппой(Объект)|о.м.ОбщегоНазначения|Проверяет, является ли элемент справочника или плана видов характеристик группой элементов|
|Функция ИдентификаторОбъектаМетаданных|о.м.ОбщегоНазначения|Возвращает ссылку, соответствующую объекту метаданных, для использования в базе данных|
|Функция ИдентификаторыОбъектовМетаданных|о.м.ОбщегоНазначения|Возвращает ссылки, соответствующие объектам метаданных, для использования в базе данных|
|Функция ОбъектМетаданныхПоИдентификатору|о.м.ОбщегоНазначения|Возвращает объект метаданных по переданному идентификатору|
|Функция ОбъектыМетаданныхПоИдентификаторам|о.м.ОбщегоНазначения|Возвращает объекты метаданных по переданным идентификаторам|
|Функция СтроковоеПредставлениеТипа(Тип)|о.м.ОбщегоНазначения|Возвращает строковое представление типа|
|Функция ОписаниеСвойствОбъекта(ОбъектМетаданных, Свойства)|о.м.ОбщегоНазначения|Возвращает таблицу значений с описанием требуемых свойств всех реквизитов объекта метаданных|
|Функция ЭтоСтандартныйРеквизит(СтандартныеРеквизиты, ИмяРеквизита)|о.м.ОбщегоНазначения|Возвращает признак того, что реквизит входит в подмножество стандартных реквизитов|
|Функция ЕстьРеквизитОбъекта(ИмяРеквизита, МетаданныеОбъекта)|о.м.ОбщегоНазначения|Позволяет определить, есть ли среди реквизитов объекта реквизит с переданным именем|
|Функция ОписаниеТипаСостоитИзТипа(ОписаниеТипа, ТипЗначения)|о.м.ОбщегоНазначения|Проверить, что описание типа состоит из единственного типа значения и совпадает с нужным типом|
|Функция ОписаниеТипаСтрока(ДлинаСтроки)|о.м.ОбщегоНазначения|Создает объект ОписаниеТипов, содержащий тип Строка|
|Функция ОписаниеТипаЧисло(Разрядность, РазрядностьДробнойЧасти = 0, Знач ЗнакЧисла = Неопределено) |о.м.ОбщегоНазначения|Создает объект ОписаниеТипов, содержащий тип Число|
|Функция ОписаниеТипаДата(ЧастиДаты)|о.м.ОбщегоНазначения|Создает объект ОписаниеТипов, содержащий тип Дата|
|Функция ОписаниеТипаВсеСсылки()|о.м.ОбщегоНазначения|Возвращает описание типа, включающего в себя все возможные ссылочные типы конфигурации|
|Функция ЗначениеВСтрокуXML(Значение)|о.м.ОбщегоНазначения||
|Функция ЗначениеИзСтрокиXML(СтрокаXML)|о.м.ОбщегоНазначения||
|Функция ОбъектXDTOВСтрокуXML(Знач ОбъектXDTO, Знач Фабрика = Неопределено)|о.м.ОбщегоНазначения||
|Функция ОбъектXDTOИзСтрокиXML(Знач СтрокаXML, Знач Фабрика = Неопределено)|о.м.ОбщегоНазначения||
|Процедура СкопироватьСтрокиВБуферОбмена(ТабличнаяЧасть, ВыделенныеСтроки, Источник = Неопределено)|о.м.ОбщегоНазначения|Помещает выделенные строки табличной части во внутренний буфер обмена|
|Процедура СкопироватьВБуферОбмена(Данные, Источник = Неопределено)|о.м.ОбщегоНазначения|Помещает произвольные данные во внутренний буфер обмена, откуда их можно получить с помощью СтрокиИзБуфераОбмена|
|Функция СтрокиИзБуфераОбмена()|о.м.ОбщегоНазначения|Получает строки табличной части, помещенные во внутренний буфер обмена с помощью СкопироватьСтрокиВБуферОбмена|
|Функция ПустойБуферОбмена(Источник = Неопределено)|о.м.ОбщегоНазначения|Проверяет наличие сохраненных данных во внутренний буфере обмена|
|Процедура ВыполнитьМетодКонфигурации(Знач ИмяМетода, Знач Параметры = Неопределено)|о.м.ОбщегоНазначения|Выполнить экспортную процедуру по имени с уровнем привилегий конфигурации|
|Процедура ВыполнитьМетодОбъекта(Знач Объект, Знач ИмяМетода, Знач Параметры = Неопределено)|о.м.ОбщегоНазначения|Выполнить экспортную процедуру объекта встроенного языка по имени|
|Процедура ВыполнитьВБезопасномРежиме|о.м.ОбщегоНазначения|Выполняет произвольный алгоритм на встроенном языке 1С:Предприятия, предварительно устанавливая|
|Функция ВычислитьВБезопасномРежиме|о.м.ОбщегоНазначения|Вычисляет переданное выражение, предварительно устанавливая безопасный режим выполнения кода|
|Функция РаспределитьСуммуПропорциональноКоэффициентам|о.м.ОбщегоНазначения|Выполняет пропорциональное распределение суммы в соответствии коэффициентам|
|Процедура ЗаполнитьКоллекциюЭлементовДереваДанныхФормы(КоллекцияЭлементовДерева, ДеревоЗначений|о.м.ОбщегоНазначения|Процедура предназначена для заполнения реквизита формы типа ДанныеФормыДерево|
|Функция СоздатьВременныйКаталог|о.м.ОбщегоНазначения||
|Процедура УдалитьВременныйКаталог|о.м.ОбщегоНазначения||
|Функция ОбъектПоПолномуИмени(ПолноеИмя)|о.м.ОбщегоНазначения|Устарела. Создает и возвращает экземпляр отчета или обработки по полному имени объекта метаданных|
|Функция НайтиОшибкуДоступностиРеквизитовОбъекта|о.м.ОбщегоНазначения|Выполняет поиск проверяемых выражений среди реквизитов объекта метаданных|
|Процедура УстановитьПометкуУдаленияДляОбъектов(Результат, Знач УдаляемыеСсылки, Знач ПараметрыВыполнения|о.м.ОбщегоНазначения||
|Функция УстановитьПометкуУдаления(Результат, Знач УдаляемаяСсылка, Знач ВсеМестаИспользования, Знач ПараметрыВыполнения,|о.м.ОбщегоНазначения||
|Функция ОписаниеОбъекта(Знач ОбъектМетаданных|о.м.ОбщегоНазначения|Возвращает структуру реквизитов|
|Процедура ЗаписатьОбъект(Знач Объект, Знач ПараметрыЗаписи)|о.м.ОбщегоНазначения||
|Функция СравниваемыеКолонки(Знач КоллекцияСтрок, Знач ИменаКолонок, Знач ИсключаяКолонки|о.м.ОбщегоНазначения||
|Функция СравнитьМассивы(Знач Массив1, Знач Массив2)|о.м.ОбщегоНазначения||
|Функция СкопироватьСтруктуру(СтруктураИсточник, ФиксироватьДанные)|о.м.ОбщегоНазначения|#Область СкопироватьРекурсивно|
|Функция СкопироватьСоответствие(СоответствиеИсточник, ФиксироватьДанные)|о.м.ОбщегоНазначения|#Область СкопироватьРекурсивно|
|Функция СкопироватьМассив(МассивИсточник, ФиксироватьДанные|о.м.ОбщегоНазначения|#Область СкопироватьРекурсивно|
|Функция СкопироватьСписокЗначений(СписокИсточник, ФиксироватьДанные)|о.м.ОбщегоНазначения|#Область СкопироватьРекурсивно|
|Процедура ПроверитьОбъектМетаданныхСуществует(ПолноеИмя)|о.м.ОбщегоНазначения||
|Процедура ХранилищеСохранить|о.м.ОбщегоНазначения||
|Функция ХранилищеЗагрузить|о.м.ОбщегоНазначения||
|Процедура ХранилищеУдалить|о.м.ОбщегоНазначения||
|Функция МенеджерОбъектаПоИмени(Имя)|о.м.ОбщегоНазначения|Возвращает менеджер объекта по имени|
|Функция ВызватьФункциюКонфигурации(Знач ИмяМетода, Знач Параметры = Неопределено)|о.м.ОбщегоНазначения|Вызвать экспортную функцию по имени с уровнем привилегий конфигурации|
|Функция ВызватьФункциюОбъекта(Знач Объект, Знач ИмяМетода, Знач Параметры = Неопределено)|о.м.ОбщегоНазначения|Вызвать экспортную функцию объекта встроенного языка по имени|
||||
||||
||||
||||
||||
