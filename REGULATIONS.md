# Регламент публичного трекера ошибок и предложений 1С:EDT
Данный регламент регулирует публичную часть взаимодействия сообщества пользователей 1C:EDT и разработчиков 1C:EDT при работе с размещенными ошибками и предложениями.

Процесс работы над задачами в публичном трекере состоит из следующих последовательных этапов:
- Регистрация ошибок/задач/предложений - выполняется пользователями 1C:EDT и/или разработчиками 1C:EDT
- Отбор задач для анализа - выполняется разработчиками 1C:EDT, с участием пользователей 1C:EDT
- Анализ отобранных задач - выполняется разработчиками 1C:EDT для отобранных ранее задач
- Приоритизация и планирование - выполняется разработчиками 1C:EDT, результатом этого этапа является дополнение публичного плана по реализации задач/исправлению ошибок
- Реализация и завершение - выполняется разработчиками 1C:EDT, по результатам производится обновление информации в трекере

## Регистрация ошибок/задач/предложений
Для регистрации ошибок/задач/предложений необходимо иметь активный аккаунт GitHub.

Пользователь может создать один из трех видов задач:
- Ошибка - обычные ошибки, рассматриваемые командой 1C:EDT в рамках стандартного процесса отбора и анализа (см. далее)
- Критическая ошибка - ошибка, делающая невозможной работу с 1C:EDT, и рассматриваемая командой 1C:EDT вне очереди
- Предложение/Запрос/Задача - регистрация идей/предложений/пожеланий пользователей к расширению функциональности 1C:EDT
Каждая задача регистрируется через соответствующий шаблон задачи и требует специфичного набора данных для создания.

*Команда 1C:EDT призывает сообщество к аккуратному рассмотрению списка существующих проблем перед репортингом проблемы. Создание дубля никак не увеличит шансы на скорейшую адресацию проблемы (наоборот - разделит приоритет сообщества на несколько аналогичных записей). Команда EDT оставляет за собой право закрытия дублей с указанием ссылки на оригинальную проблему.*

## Отбор задач для анализа
Отбор задач для последующей обработки осуществляется тремя способами:
- Критические ошибки
- Отбор с учетом приоритетов, заданных сообществом
- Свободный отбор командой 1C:EDT

Признаком отбора задачи является помещение ее в план проекта в категорию **"Требует анализа"** разработчиками 1C:EDT. 

## Критические ошибки
Критические ошибки всегда рассматриваются вне зависимости от текущих приоритетов/запланированных задач/отобранных задач в максимально короткие сроки. Критические ошибки обрабатываются как дополнение к другим способам отбора, а не как замена.
Пожалуйста, ознакомьтесь с [критериями критичности ошибок](TASK_CLASSIFICATION.md). Команда 1C:EDT оставляет за собой право смены классификации несоответствующих критериям критических ошибок.

**Помните, что каждая критическая ошибка требует времени команды для рассмотрения и анализа, и это время будет взято из времени реализации уже отобранных/запланированных задач.**

## Отбор с учетом приоритетов, заданных сообществом
Команда 1C:EDT обязуется отбирать **N (N>=1)** из топ-листа обычных задач вне зависимости от типа (ошибки, предложения, и т.п.) для последующего анализа и включения в дальнейший план в соответствии с определяемыми в ходе анализа приоритетами. Отбор производится в начале каждой итерации разработки 1C:EDT (обычно 3 недели, информация об итерациях будет опубликована в проекте)

Принципы отбора:
- Положение в топе определяется по суммарному количеству голосов участников комьюнити, отданных задаче или ошибке
- Из выбора исключаются задачи/ошибки с менее чем 2 голосами
- Голосом считается постановка маркера :+1: в запись задачи. Любые другие маркеры не учитываются при оценке приоритета
- Отбор осуществляется в начале очередной итерации, однако без жестких ограничений по времени по времени завершения отбора
- Конкретный размер отбора для каждой итерации определяется командой 1C:EDT и публикуется в информации по проекту для каждого следующего периода отбора. Размер зависит от текущих планов команды и ее операционной емкости. Минимум в 1 задачу гарантируется.
(предупреждение) *Внимание - отбор задачи означает включение этой задачи в публичный план с соответствующим приоритетом (см. далее), но не обязательство по реализации в рамках текущего milestone-а. *

## Свободный отбор командой 1C:EDT
В дополнение к отбору силами сообщества, команда 1C:EDT оставляет за собой право рассматривать вне очереди любые ошибки/задачи из наличествующего списка без объяснения причин. Данный отбор идет именно как отбор дополнительных задач к уже отобранным комьюнити. 

## Анализ отобранных задач
Отобранные ранее задачи анализируются силами команды 1C:EDT во временных рамках целевого milestone-а, с активным участием авторов/других участников комьюнити. В случае невозможности воспроизведения/непредоставления дополнительных данных, требуемых для расследования проблемы пользователями, команда 1C:EDT оставляет за собой право выброса отобранной ошибки из плана до момента получения деталей, либо закрытия при неполучении данных в дальнейшем.

## Приоритизация и планирование
Планирование сроков выполнения задачи производится силами команды 1C:EDT и привязывается к определенной итерации 1C:EDT. В зависимости от сути проблемы/задачи, командой определяется приоритет задачи/ошибки.
С критериями выбора приоритета можно ознакомиться [здесь](TASK_CLASSIFICATION.md).

При несогласии с выставленным приоритетом, автор/комьюнити могут привести свои аргументы, финальное решение остается за командой 1C:EDT.

## Реализация и завершение
Реализация производится в рамках стандартного процесса команды 1C:EDT. Наличие задачи в плане не означает гарантию реализации, по причине возможности возникновения более приоритетных задач в плане (критичные ошибки и т.п.)

Все неприоритетные задачи идут строго после реализации всех запланированных приоритетных задач.

В случае незавершения задачи на итерации - производится перепланирование и перенос задачи на следующие итерации. 