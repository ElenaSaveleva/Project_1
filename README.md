# Проект 1. Анализ резюме из HeadHunter
  (ссылка на проект)


## Оглавление
1. [Описание проекта](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Описание-проекта)
2. [Какой кейс решаем?](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Какой-кейс-решаем)
3. [Краткая информация о данных](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Краткая-информация-о-данных)
4. [Этапы работы над проектом](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Этапы-работы-над-проектом)
5. [Результат](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Результат)
6. [Выводы](https://github.com/Maria-27A/game/blob/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Выводы)


### Описание проекта
На основе базы резюме, выгруженной с сайта поиска вакансий hh.ru, необходимо подготовить первичные данные для построения модели, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. 


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)


### Какой кейс решаем?
Нужно предварительно подготовить имеющиеся данные путем их изучения, преобразования с возможностью дальнейшего исследования и проведения очистки, что позволит в дальнейшем построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.


**Условия:**
- Каждая часть проекта представляет собой блок практических заданий, которые небходимо выполнить в шаблоне jupyter-ноутбука
- Задания должны выполняться последовательно
- При выполнении проекта также необходимо ответить на контрольные вопросы на платформе.


**Метрика качества:**
Результаты оцениваются согласно требованиям, указанным к проекту. 
Необходимо: ответить на контрольные вопросы (максимум 30 баллов), сдать проект на проверку, загрузив ноутбук-шаблон со своим решением на GitHub (максимум 10 баллов)


**Что практикуем:**
Учимся корректно писать код на Python для анализа и преобразования исходных данных, работать с основами IDE, практикуем методы очистки данных, навыки по представлению проекта на GitHub


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)


### Краткая информация о данных
В данном проекте первоначальные данные представлены в виде датасета размером: 44744 строки, 12 столбцов, типа object, в отдельных столбцах присутствуют пропуски и дубликаты. В связи с этим необходимо более детально проанализировать структуру первоначальных данных, сделать выводы о дальнейших преобразованиях. 


-  dst-3.0_16_1_hh_database.csv - база резюме, выгруженная с сайта поиска вакансий hh.ru
-  ExchangeRates.csv - курсы валют


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)


### Этапы работы над проектом
- Ознакомление с описанием задачи
- Базовый анализ исходных данных
- Преобразование данных
- Разведывательный анализ
- Очистка данных
- Проверка соответствия результата выполнения кода условию, приведенному в метрике качества
- Проверка соответствия написанного кода стандарту PEP8
- Оформление проекта
- Загрузка проекта на GitHub 


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)


### Результат
Проект c корректным выполнением кейса "Анализ резюме из HeadHunter " представлен в репозитории на GitHub


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)


### Выводы
В процессе выполнения кейса первоначальные данные были проанализированы, преобразованы, проведен разведывательный анализ данных с последующей визуализацией результатов с целью выявления взаимосвязей между признаками, данные были очищены от пропусков и дубликатов. Таким образом первоначальный датасет подготовлен для дальнейшего использования при построении требуемой модели. 


:arrow_up:[к оглавлению](https://github.com/Maria-27A/game/tree/main/skillfactory/PROJECT_1.Resume_analysis_from_HeadHunter/README.md#Оглавление)





asttokens==2.0.8

	attrs==22.1.0

	backcall==0.2.0

	colorama==0.4.5

	contourpy==1.0.5

	cycler==0.11.0

	debugpy==1.6.3

	decorator==5.1.1

	entrypoints==0.4

	executing==1.0.0

	fastjsonschema==2.16.2

	fonttools==4.37.4

	ipykernel==6.15.1

	ipython==8.4.0

	jedi==0.18.1

	jsonschema==4.16.0

	jupyter-core==4.11.1

	jupyter_client==7.3.5

	kiwisolver==1.4.4

	matplotlib==3.6.0

	matplotlib-inline==0.1.6

	nbformat==5.7.0

	nest-asyncio==1.5.5

	numpy==1.23.2

	packaging==21.3

	pandas==1.4.4

	parso==0.8.3

	pickleshare==0.7.5

	Pillow==9.2.0

	plotly==5.10.0

	prompt-toolkit==3.0.30

	psutil==5.9.1

	pure-eval==0.2.2

	Pygments==2.13.0

	pyparsing==3.0.9

	pyrsistent==0.18.1

	python-dateutil==2.8.2

	pytz==2022.2.1

	pywin32==304

	pyzmq==23.2.1

	seaborn==0.12.0

	six==1.16.0

	stack-data==0.5.0

	tenacity==8.1.0

	tornado==6.2

	traitlets==5.3.0

	wcwidth==0.2.5


