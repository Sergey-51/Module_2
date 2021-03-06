## задача проекта:
	необходимо провести разведывательный анализ данных 

__________________________________________________________________________________________________  

## В рамках проекта необходимо сделать следующее:

**1. Провести первичную обработку данных.**  
**2. Посмотреть на распределение признака для числовых переменных и устранить выбросы.**  
**3. Оценить количество уникальных значений для номинативных переменных.**  
**4. По необходимости преобразовать данные.**  
**5. Провести корреляционный анализ количественных переменных.**  
**6. Отобрать некоррелирующие переменные.**  
**7. Проанализировать номинативные переменные и устранить те, которые не влияют на предсказываемую величину (в нашем случае — на переменную score).**  
**8. Сформулировать выводы относительно качества данных и тех переменных, которые будут использованы в дальнейшем построении модели.**  

__________________________________________________________________________________________________  

К проекту прикреплено несколько файлов:

1. Project 2 - EDA.ipynb --- выполнение проекта в Jupyter Notebook
2. stud_math.csv --- исходные данные к проекту
3. stud_math_description.csv --- описание исходных данных к проекту
4. final_set.csv --- финальный набор данных для моделирования (результат проекта)
5. final_set_description.csv --- мои выводы по признакам по мере заполнения пропусков данных.
6. pre_final_set.csv --- набор данных до удаления ненужных столбцов, также содержит информацию по измененным и заполненным строкам.

__________________________________________________________________________________________________  

**Основной мой вывод по проекту - всегда дважды проверять данные на наличие пропусков, при их наличии корреляционный анализ не провести.** 

__________________________________________________________________________________________________  

Ответы на вопросы саморефлексии:

1. Какова была ваша роль в команде?
	Делал всё сам.
2. Какой частью своей работы вы остались особенно довольны?
	Доволен тем, что проект считаю получившимся. И не смотря на то, что он является необязательным, я считаю правильным его надо делать обязательно.
3. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?
	Не получились работа с пропусками. Первоначально я считал ,что все их нашел и где надо исправил, а когда дошел до корреляционного анализа - то потратил просто уйму времени прежде чем взглянул на данные которые пытался анализировать. И вот тут мне стало понятно, что надо переделывать весь проект, тк я сильно промахнулся в работе с пропущенными данными.
4. Что интересного и полезного вы узнали в этом модуле?
	Функции надо писать аккуратно, они сильно упрощают жизнь, но также и усложняют , особенно когда сильно веришь, что они полностью корректные.
	В этом случае найти ошибку становится очень тяжело.
5. Что является вашим главным результатом при прохождении этого проекта?
	Главный результат - что я справился с пропусками, пусть и пришлось делать это дважды.
6. Какие навыки вы уже можете применить в текущей деятельности?
	Могу дополнять исходные данные новыми показателями, для удобства анализа.
7. Планируете ли вы дополнительно изучать материалы по теме проекта?
	Хотелось бы изучить, а как собственно написанные уже мной функции можно включать в новые проекты, чтобы не заниматься простым копированием (в этом случае будет тяжело потом найти последнюю версию функции).
	
	
Файл проект получился крайне большим 27.8Мб (ограничения в задании на размер файла нету), есть подозрение, что он из-за этого не отображается в браузере (видимо надо его скачивать и смотреть локально).
