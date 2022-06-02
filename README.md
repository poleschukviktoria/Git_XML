# Git_XML
21.   Создать внешний репозиторий c названием XML.
>Git_XML

22. Клонировать репозиторий XML на локальный компьютер.  
>git clone git@github.com:poleschukviktoria/Git_XML.git

23. Внутри локального XML создать файл “new.xml”.  
>cd /d/V_ksendzov/Git_XML/Git_XML/
>touch new.xml
>git status     

24. Добавить файл под гит.  
>git add new.xml
>git status   

25. Закоммитить файл.  
>git commit -m "add new.xml file"
>git status 

26. Отправить файл на внешний GitHub репозиторий.  
>git push

27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
>cat >> new.xml  
<?xml version="1.0" encoding="utf-8"?>
<new>
	<last_name>Полещук</last_name>
	<first_name>Виктория</first_name>
	<age>39</age>
	<number_of_pets>0</number_of_pets>
  	<salary>800</salary>
</new>  
>Нажать Ctrl+D  
>cat new.xml

28. Отправить изменения на внешний репозиторий.  
>git status    
>git commit -am "changes new.xml file"  
>git push  

29. Создать файл preferences.xml  
>touch preferences.xml  

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
>cat >> preferences.xml  
<?xml version="1.0" encoding="utf-8"?>
<favorite>
	<movie>Список Шиндлера</movie>
	<series>Ганнибал</series>
	<food>Вкусная</food>
 	<season>Лето</season>
	<country>Португалия</country>
</favorite>  
>Нажать Ctrl+D  
>cat preferences.xml  

31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
>cat >> skills.xml  
<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<QA>Git, GitHub, API, HTTP/HTTPS, Charles, Fiddler, Android studio, ADB  Web testing, Mobile testing, Proxy, VPN, SQL, JMeter, Scrum
</skills>  
>Нажать Ctrl+D  
>cat skills.xml   

32. Сделать коммит в одну строку.  
>git status     
>git add . ; git commit -m "add preferences.xml and skills.xml files with info"  

33. Отправить сразу 2 файла на внешний репозиторий.  
>git push  

34. На веб интерфейсе создать файл bug_report.xml.  
>На GitHub создать файл bug_report.xml  

35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
>Закоммитить bug_report.xml файл на GitHub  

36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
>На GitHub модифицировать файл bug_report.xml  
<?xml version="1.0" encoding="UTF-8"?>
<ID>000</ID>
<Title>заголовок</Title>
<Environment>окужение</Environment>
<Precondition>предусловие</Precondition>
<STR>шаги воспроизведения бага</STR>	
<AR>фактический результат</AR>
<ER>ожидаемый результат</ER>	
<Attachments>скриншот или видео</Attachments>
<Severity>
	<type>Blocker</type>
	<type>Critical</type>
	<type>Major</type>
	<type>Minor</type>
	<type>Trivial</type>
</Severity>
<Priority>
	<type>High</type>
	<type>Medium</type>
	<type>Low</type>
</Priority>  

37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
>Закоммитить bug_report.xml файл на GitHub  

38. Синхронизировать внешний и локальный репозиторий XML  
>git fetch  
>git pull  
