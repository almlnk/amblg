# Классические и современные определения дефекта (бага)

В [учебных программах](2016-08-14-educational-programs-exam-questions-and-literature.md) по дисциплине "Обеспечение качества и тестирование программ" есть вопросы "Классические и современные определения дефекта (бага)" и "Типы дефектов". В программе обучения базового уровня International Software Testing Qualifications Board "Сертифицированный тестировщик" тема детализируется пунктом «Используя примеры, объяснить и сравнить термины ошибка, дефект, недочет, отказ и соответствующие термины просчет и помеха».

Содержание:

1. [«Искусство тестирования программ», Глендфорд Майерс](#mayers)
2. [«Стандартный глоссарий терминологии по программированию» Института инженеров электротехники и электроники](#ieee)
3. [«Основы программной инженерии (по SWEBOK). Программная инженерия. Тестирование программного обеспечения»](#swebok)
4. [«Быстрое тестирование» Роберт Калбертсон, Крис Браун, Гэри Кобб](#rkb)
5. [«Тестирование черного ящика. Технологии функционального тестирования программного обеспечения систем», Борис Бейзер](#beizer)
6. [«Стандартный глоссарий терминов, используемых в тестировании программного обеспечения» ISTQB](gistqb)
7. [«Ключевые процессы тестирования. Планирование, подготовка, проведение, совершенствование», Рекс Блэк](#black)
8. [«Верификация программного обеспечения», С.В. Синицын, Н.Ю. Налютин](#verif)
9. [«Основы инженерии качества программных систем», Филипп Андон, Галина Коваль, Татьяна Коротун, Екатерина Лаврищева, В. Суслов](#andon)
10. [«Тестирование Дот Ком, или Пособие по жестокому обращению с багами в интернет-стартапах», Роман Савин](#savin)
11. [IEEE Standard Classification for Software Anomalies](#ieee1044) 
12. [«Сертифицированный тестировщик Программа обучения Базового уровня» ISTQB](#istqbadv)
13. [«Краткие основы тестирования программного обеспечения», А.Н. Коробейник](#korobeynik)

### «Надежность программного обеспечения» <a name="mayers"></a>

**Гленфорд Майерс**. Москва, издательство "Мир", 1980 год. 11, 21 страницы:

![Glenford Myers](https://lh3.googleusercontent.com/zOBmf_WDFH2lPkMkfjW3HKnEjOHvPKkoY2DDurlymWo-c4S8ODU06BNwWGGW_IGCG4NcJULS5bgGFH2MqHk02gMEGYBhanEue6pIiE0fjDlPLoQH6F-ZmlTnVZivdjtBKLAeo-mYXoZ9_uH6g5vqYA_iqnGsuZD5AQ0IYVP8PnV4WWntb4D8Fp6HwjWpBguQGeDNj93nUUMOE6Na8x1w0Ym0LhthsNJShKoXfTtWwrlpN6GVrPXQXL1Ngch--4qdh0OlTlmhWE3lujx8JTH3OaNjvgNsqEdI4OATaFpstOtn-a7L71MpxFr7FsWouFxF1HJPnCY71Tz9nZdUGj367ORqEfQ0l9m8HQrZPk-BEJWNNRpOiF07Y8aVFwsRclA6J9ke06xIaL29-sWOYKa8NYhcUo8ledZnjMVsBUv2MmhM-BKqrRh7tpEQuOd5uRH7YotaEdqic5qKluhm2Mq4ONYxoyGJgCuFzhspz2GhA0Lzx3Si4iC1QY5O3I_ICbYLJjMlBHr5GREsNxnz52XS_trmpAL-r8LG1bQJeQgO7sTQ9LZSnMmI1ZDUGokdW_Q26LV6BalS7JhwN-X3_INd-OSGkkhYAPdWzFYyHa2I1xRRXqFQhbcgZHD_zgZ_YiN2Pe_oCwwvzokFrtfW5nFIu34j-PVMTKlG=w624-h469-no)

> Ошибка в программном обеспечении - это невыполнение того, что пользователь разумно ожидает от программного обеспечения... Ошибки в программном обеспечении не являются внутренним его свойством... Коротко говоря, наличие ошибок - функция как самого программного обеспечения, так и ожиданий его пользователей... Отказ программного обеспечения - это проявление ошибки в программном обеспечении.
>
> Единственная важная причина ошибок в программном обеспечении - неправильный перевод информации из одного представления в другое... Создание программного обеспечения в этом случае - просто совокупность процессов трансляции, то есть перевода исходной задачи в различные промежуточные решения, пока наконец не будет получен подробный набор машинных команд. Когда не удается полно и точно перевести некоторое представление задачи или решения в другое, более детальное, тогда и возникают ошибки в программном обеспечении.

### «Стандартный глоссарий терминологии по программированию» Института инженеров электротехники и электроники <a name="ieee"></a>

Institute of Electrical and Electronics Engineers **Std 610.12-1990**, IEEE Standard Glossary of Software Engineering Technology. 14, 31, 32, 65, 70, 73, 78 страницы:

> Bug. See: error; fault. 
>
> Error. (1) The difference between a computed, observed, or measured value or condition and the true, specified, or theoretically correct value or condition. For example, a difference of 30 meters between a computed result and the correct result. (2) An incorrect step, process, or data definition. For example, an incorrect instruction in a computer program. (3) An incorrect result. For example, a computed result of 12 when the correct result is 10. (4) A human action that produces an incorrect result. For example, an incorrect action on the part of a programmer or operator. Note: While all four definitions are commonly used, one distinction assigns definition 1 to the word “error,” definition 2 to the word “fault,” definition 3 to the word “failure,” and definition 4 to the word “mistake”. See also: dynamic error; fatal error; indigenous error; semantic error; syntactic error; static error; transient error
>
> Fault. (1) A defect in a hardware device or component; for example, a short circuit or broken wire. (2) An incorrect step, process, or data definition in a computer program. Note: This definition is used primarily by the fault tolerance discipline. In common usage, the terms “error” and “bug” are used to express this meaning. See also: data-sensitive fault; program sensitive fault; equivalent faults; fault masking; intermittent fault.
>
> Dynamic error. An error that is dependent on the time-varying nature of an input. Contrast with: static error. 
>
> Fatal error. An error that results in the complete inability of a system or component to function.
>
> Indigenous error. A computer program error that has not been purposely inserted as part of an error-seeding process. 
>
> Semantic error. An error resulting from a misunderstanding of the relationship of symbols or groups of symbols to their meanings in a given language. Contrast with: syntactic error. 
>
> Syntactic error. A violation of the structural or grammatical rules defined for a language; for example, using the statement B + C = A in Fortran, rather than the correct A = B + C. Syn: syntax error. Contrast with: semantic error. 
>
> Static error. An error that is independent of thetime-varying nature of an input. Contrast with: dynamic error. 
>
> Transient error. An error that occurs once, or at unpredictable intervals. See also: intermittent fault; random failure. 
>

### «Основы программной инженерии (по SWEBOK). Программная инженерия. Тестирование программного обеспечения» <a name="swebok"></a>

На базе IEEE Guide to SWEBOK**® 2004, Сергей Орлик. 4 страница:

![Sergey Orlik](https://lh3.googleusercontent.com/7p7-DqjtdIMSf1jB5arBBgQON4vsiCVVdjKLFKh7uyJXOGhLTzU7RtRQ7kLe8ohBPOBiRDN0tLKa0Y2cFO6pKSWF90T-hljF-BpWCxaNCuYn6CG6YZdGmN4PDJS_KFh6j0A7BC81dISRIQOrSn6maqWW4xes71rB13lJEjCgYVz-GUcPFs_himX9SI9-slxEHiNTgkbUTt9RRt0oc8qZtFRLA6RyapgNrtg5cmGdHT9pgtRgd9GspafTBGmplHh2wnDxKffSS62s0NnVAnmdGjHcfcsCGQvrXolsBfpQNrqlWVTMuUb-4nDBderiS9cQ_lx_Dekbozh8MzMfXbg3oby9C5AzJ9evj_BA4c81sYZ9GQKl9_5nLyG6uaLiWdP-WyynnM6iOYPQGgYO18itHYRrGHxyKpSbJjsAViZIXNCzEMNPXRXRLkAmSYvWjqN9Co3qQuRNDebpTP09YyAuI1OjLq_7BjI8FS5qM2aQUh1rP2oIw4KA9vsNA8R6yRzMmOYa-mBk6Bk1AYOi2_heouIm2Uz3HEKhjyetxZL5_WRt-hcqOixXM6srcwOSBakl7V_8IoT68zdHJuVsHEdf4FIOWdocvNSGjFAOabphUyyjM48SEWTx_3lKyNbrdoJzs76HhpWlbZNaQaCmOUL650U87DGLPI-T=w670-h300-no)

> Недостаток (fault), дефект (defect) - причина нарушения работы прикладной системы.
>
> Сбой (failure) - наблюдаемый нежелательный эффект, вызываемый причиной нарушения работы прикладной системы.
>
> Ошибка - в зависимости от контекста, может описывать и как причину сбоя, и сам сбой.
>

### «Быстрое тестирование» <a name="rkb"></a>

**Роберт Калбертсон, Крис Браун, Гэри Кобб**. Издательский дом "Вильямс", 2002. 17-18 страницы:

> ...Понятие дефекта (bug). Говоря простыми словами, программная ошибка— ни что иное, как изъян в разработке программного продукта, который вызывает несоответствие ожидаемых результатов выполнения программного продукта и фактически полученных результатов. Дефект может возникнуть на стадии кодирования, на стадии фор­мулирования требований или на стадии проектирования, либо же его причина может крыться в некорректной конфигурации или данных. Дефектом может быть также что-то другое, что не соответствует ожиданиям заказчика и что может быть, а может и не быть определено в спецификации программного продукта. Более подробное описание терминологии дефектов приводится во врезке 1.1...
>
> Врезка 1.1. Долговечность дефекта может быть описана следующим образом. Дефект возникает в результате того, что человек допускает ошибку (error), осуществляя некоторый вид деятельности, который имеет отношение к разработке программного обеспечения. К упомянутым видам деятельности относятся, например, формулирование требований, проектирование программы или написание программного кода. Эта ошибка вкрадывает­ся в рабочий продукт (перечень требований, проектный документ или программный код) в виде неисправности (fault).
>
> До тех пор пока эта неисправность (известная еще как дефект (bug, defect)) присутствует в рабочем продукте, она может служить причиной появления других дефектов. На­пример, если неисправность, допущенная в перечне требований, остается необнаруженной, вполне вероятно, что это приведет к возникновению соответствующих ошибок в проекте системы, в проекте программы, в программном коде и даже в документации для пользователя.
>
> Дефект остается необнаруженным до тех пор, пока не произойдет отказ. Ведь именно тогда пользователь или тестировщик замечает, что система не выполняет возложенных на нее функций. На стадии системных испытаний цель специалиста по тестированию состоит в том, чтобы вызвать сбой программы, обнаружить и задокументировать связанные с ним дефекты, а затем удалить их из системы. В идеальном случае долговечность дефекта ограничена моментом, когда он обнаруживается средствами статичного или динамического тестирования и успешно устраняется. 
>

### «Тестирование черного ящика. Технологии функционального тестирования программного обеспечения систем» <a name="beizer"></a>

**Борис Бейзер**. СПб: Питер, 2004. 28 страница:

> Симптом (отказ IEEE94). Наблюдаемое аномальное поведение любого объекта (не обязательно тестируемого), такое как несоответствие требованиям или возникновение незапланированных явлений.
>
> Ошибка (сбой IEEE94). Просчет в проектировании, ведущий к возникновению симптомов у какого-либо объекта (тестируемого и не только) при прохождении этим объектом определенного теста.
>

### «Стандартный глоссарий терминов, используемых в тестировании программного обеспечения» ISTQB <a name="gistqb"></a>

> Версия 2.3 от 9 июля 2014 года, International Software Testing Qualifications Board. Ред. пер. Александр Александров. 17, 36 и 38 страницы:
>
> Недочет (fault) - см. "дефект". Дефект (fault) - это изъян в компоненте или системе, который может привести компонент или систему к невозможности выполнить требуемую функцию, например, неверный оператор или определение данных. Дефект, обнаруженный во время выполнения, может привести к отказам компонента или системы.
>
> Отказ (failure) - это отклонение компонента или системы от ожидаемого выполнения, эксплуатации или результата. (N. Fenton (1991), Software Metrics: a Rigorous Approach, Chapman & Hall, ISBN 0-53249-425).
>
> Ошибка (error) - это действие человека, которое приводит к неправильному результату. [IEEE610].
>
> Помеха (bug) - см. "дефект".
>
> Просчет (mistake) - см. "ошибка". 
>

### «Ключевые процессы тестирования. Планирование, подготовка, проведение, совершенствование» <a name="black"></a>

**Рекс Блэк**, Москва, Лори, 2006, 528/545 страницы:

> Ошибка, дефект (Bug, Defect). Проблема, которая вызывается или может вызывать неадекватное выполнение системой одного или нескольких обоснованных ожиданий качества заказчика/пользователя.
>

### «Верификация программного обеспечения» <a name="verif"></a>

**С.В. Синицын, Н.Ю. Налютин**. МИФИ, Курс лекций, 2006, 19 страница:

> Ошибка - действие программиста на этапе разработки, которое приводит к тому, что в программном обеспечении содержится внутренний дефект, который в процессе работы программы может привести к неправильному результату.
>
> Отказ – непредсказуемое поведение системы, приводящее к неожидаемому результату, которое могло быть вызвано дефектами, содержащимся в ней.
>

### «Основы инженерии качества программных систем» <a name="andon"></a>

**Филипп Андон, Галина Коваль, Татьяна Коротун, Екатерина Лаврищева, В. Суслов**. Академпериодика, 2007. 218-220 страницы:

> Ни за рубежом, ни в Украине, не достигнуто согласия по определению основных понятий в этой области – дефект, ошибка, отказ. Эти понятия по-разному определяются не только в научной литературе по качеству и надежности программного обеспечения, но и в стандартах. Проще всего поступили разработчики стандарта IEEE Std.1044 «Standard Classification for Software Anomalies» (Стандартная классификация аномалий программного обеспечения), которые предпочли использовать единый термин «аномалия» (anomaly) вместо других – error, fault, failure, incident, flaw, problem, gripe, glitch, defect или bug - что для целей этого стандарта оправданно.
>
> ![Relationship-errors,-defects-and-failures](https://lh3.googleusercontent.com/VkeucJmEdlr5Em5Hr0__Qd6h0mh4FnTwVhy3AqbacK_gaYI5H4J1e2px9PYfeFSGLX_JuslT4jGkm9vgjfchDwbJOMDkMyY3p5V8lmGOCmrLNUAwWJxwRwKsWl62KvADZyRB6_GYN9MDfduBWkxycnBhXvzjZQyesHe_8_laW0zdwMJWVZSvaMddTGgZ_fZvG8h2Q6KhE4AVdJT3MmYklRW89xIisJSllx-c5oV6wmDTcmWztUc3JO508bqs5YBvNdE5VVJgED5l8y9sTxSpZ1rWGBktYL6S0LSqCrF_PW1jGryz6PHaLpQQ3xdSKKTXQF1wyT2Vgnra2th1M7rrqdN7n7gsO9FLYzbPTmSoOonY5jBBiVglbOhrL8qoRKv-5p-eCg1O9SWZORBFm2PhNWDB6WgB7c8nffhcBliXJuzuY3hptZYUlrfk6mGNx9T_X2f1-hgtpttzYJwMDDaA6SYcQcKKp8Nfr4T2IOWBa3EK_58k8h8R0Ejmv-K9UcH9xH3AZsY2zsihDxAdcsLTNsm6WDW4Y6QcptsxVAboOumapkYIloX-OZU7p-9QeF2N2447f31x5VrVEEZekaz0IFza8O61x2SIz_wSkEUfUOmV6nf3ZdwmgEGpAfF3IhztBLDQnkZ4YSZb7xZWAEkjwbvRJsDFELdl=w551-h610-no)
>
> Существуют глубокие причинно-следственные связи между отказами программной системы в эксплуатации, дефектами в поставляемом программном обеспечении, ошибками разработчика и изъянами в процессах создания программной системы (рисунок 5.13).
>
> Отказ (failure) - событие перехода программной системы из работоспособного состояния в неработоспособное или получения результатов, которые находятся вне области допустимых значений. Отказы программной системы могут быть обусловлены как внешними причинами (ошибками элементов среды функционирования, в том числе человека-оператора), так и внутренними причинами - дефектами в программной системы.
>
> Дефект (defect) в программной системе – запись элемента программы (кода) или текста документа (рабочего продукта), использование которой может привести к событию, заключающемуся в неправильной интерпретации этого элемента компьютером (ошибке (fault) в программе - ошибочному состоянию программы) или человеком (ошибке (error) исполнителя – заблуждению исполнителя).
>
> Дефект всегда является следствием ошибки исполнителя процесса на любом из этапов разработки. Дефектом могут обладать спецификации требований, проектные документы, тексты кода, эксплуатационная документация и т.д. Выходные рабочие документы одних процессов, содержащие не устраненные при проверке дефекты, служат входными документами для других процессов, а дефекты в них – источником ошибок исполнителей этих процессов. Кроме того, ошибки исполнителей могут являться следствием изъянов в определении процессов (неправильная последовательность действий, неправильно выбранный инструмент и др.), способствующих неправильной интерпретации исходной информации человеком и принятию неверных решений, или просто недостаточной профессиональной зрелостью. Ошибки исполнителей, в свою очередь, приводят к дефекту в рабочем продукте, и цикл «ошибка (error) – дефект (defect) – ошибка (error)» повторяется.
>
> Дефекты в коде, не обнаруженные в результате проверок текста кода, служат источником потенциальных ошибок и отказов программной системы. «Сработает» дефект или нет, зависит от того, по какому сценарию будет работать с программой пользователь, и «столкнется» ли обработчик кода с неправильным элементом.
>
> Если дефект «срабатывает» - возникает цепь ошибок, передаваемых от модуля к модулю. Если ошибка не компенсируется в программе (благодаря встроенным в программу средствам отказоустойчивости или в результате случайного «срабатывания» другого дефекта), - она может привести к аномалии в функционировании программной системы. Считать ли аномалию отказом – зависит от определения понятия отказ в спецификации требований к разрабатываемой программной системы. Обычно говорят, что в результате выполнения программы произошел инцидент (incident), который проявился в виде определенной аномалии. Последующий анализ инцидента и аномалии может показать наличие проблемы (problem) или ее отсутствие. О проблеме составляется отчет, который в виде входного документа направляется процессу «Управление решением проблем». Таким образом, схему отказа программы можно представить цепочкой дефект в коде:
>
> ```
> дефект в коде (defect) [- ошибка (fault)] - аномалия (anomaly) = отказ (failure).
> ```
>

### «Тестирование Дот Ком, или Пособие по жестокому обращению с багами в интернет-стартапах» <a name="savin"></a>

**Роман Савин**, Москва, Дело, 2007. 18 страница:

> Баг (bug) — это отклонение фактического результата (actual result) от ожидаемого результата (expected result). В соответствии с законом исключенного третьего у нас есть баг при наличии любого фактического результата, отличного от ожидаемого.
>

### IEEE Standard Classification for Software Anomalies<a name="ieee1044"></a>

IEEE Std 1044-2009, IEEE Standard Classification for Software Anomalies. 5 страница:

> For the purposes of this document, the following terms and definitions apply. The IEEE Standards
> Dictionary: Glossary of Terms and Definitions should be referenced for terms not defined in this clause.
>
> defect: An imperfection or deficiency in a work product where that work product does not meet its
> requirements or specifications and needs to be either repaired or replaced. (adapted from the Project Management Institute, A Guide to the Project Management Body of Knowledge (PMBOK®
> Guide), 4th ed. Newtown Square, PA: Project Management Institute, 2008.).
>
> NOTE—Examples include such things as 1) omissions and imperfections found during early life cycle phases and 2) faults contained in software sufficiently mature for test or operation. 

Дефект - недоделка или неполноценность в работающем продукте, когда этот рабочий продукт не соответствует требования или спецификациям к нему, нуждается в ремонте или замене.

Примечание. Примеры включает в себя: 1) упущения и недоделки, обнаруженные на ранних этапах жизненного цикла и 2) неисправности, содержащиеся в программного обеспечении, достаточно зрелом для тестирования и эксплуатации.

> error: A human action that produces an incorrect result. (adapted from ISO/IEC 24765:2009 [B17]).

Ошибка - человеческое действие, которое приводит к неверному результату.

> failure: (A) Termination of the ability of a product to perform a required function or its inability to perform within previously specified limits. (adapted from ISO/IEC 25000:2005 [B18]) (B) An event in which a system or system component does not perform a required function within specified limits. (adapted from ISO/IEC 24765:2009 [B17])
>
> NOTE—A failure may be produced when a fault is encountered. 

Неисправность - а) прекращение/окончание возможности продукта выполнять требуемые функции или неспособность выполняться в ранее установленных границах. б) событие при котором система или системный компонент не выполняют требуемое назначение в установленных рамках. 

Примечание. При возникновении неисправности может произойти сбой.

> fault: A manifestation of an error in software. (adapted from ISO/IEC 24765:2009 [B17]) 

Сбой - проявление ошибки в программном обеспечении.

> problem: (A) Difficulty or uncertainty experienced by one or more persons, resulting from an unsatisfactory encounter with a system in use. (B) A negative situation to overcome. (adapted from ISO/IEC 24765:2009 [B17])

Проблема - а) трудность или неопределенность, испытываемая одним или несколькими лицами в результате неудолетворительного взаимодействия с системой. б) отрицательная ситуация, которую необходимо преодолеть.

### «**Сертифицированный тестировщик Программа обучения Базового уровня**» ISTQB <a name="istqbadv"></a>

Версия 2011 (от 13 апреля 2011 года), International Software Testing Qualifications Board, Андрей Конушин (председатель), Александр Александров, Алексей Александров, Татьяна Смехнова, Елена Абрамова. 12/101 страница:

> Просчет - это сделанная человеком ошибка, которая порождает дефект (недочет, помеху) в программном коде или документе.
>

### «Краткие основы тестирования программного обеспечения» <a name="korobeynik"></a>

**А.Н. Коробейник**. Киев: Директ-лайн, 2012. 10 страница:

> Первый официальный отчет о дефекте в работе компьютера датируется 9-м сентября 1947 года. Грейс Хоппер работая с релейным вычислительным компьютером обнаружила сбои в работе оборудования. Разобрав компьютер её команда увидела что между движущимися частями застряла моль, что и мешало правильной работе компьютера. Насекомое было извлечено и прикреплено к журналу отчета об ошибке. Так был создан первый официальный отчет о дефекте, который и назвался в честь погибшего насекомого – Bug Report (отчет о насекомом). С тех пор дефекты в профессиональном жаргоне называются багами (bug – от англ. жук), а 9-е сентября считается днем тестировщика, профессиональным праздником.
>

### Вывод

Определение в книге Бориса Бейзера в переводе издательского дома "Питер" ужасно. Рекс Блэк в переводе издательства "Лори" также может только запутать. Андон, Коваль и Коротун начали рассказывать о различиях в терминологии задом наперед. Удивительно последовательно к описанию различий подошли  Калбертсон, Браун и Кобб.

Эта заметка-конспект является ответом на одну из тем экзаменационного вопроса вузов и ISTQB. Полный перечень вопросов привел в заметке [Учебные программы, экзаменационные вопросы и литература по обеспечению качества и тестированию программ](/2016-08-14-educational-programs-exam-questions-and-literature.md).

09.07.2017. Перейти на [Главную страницу](./)