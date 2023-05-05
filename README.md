# Тематическая классификация текстов      

<p align="justify">
Будем работать с датасетом для тематической классификации, "20 новостных групп", который состоит из примерно 20 тысяч сообщений электронной почты, распределенных по 20 категориям. Датасет состоит из двух частей — из обучающей выборки и тестовой. Суммарно 18 тысяч текстов, из них примерно две трети содержатся в обучающей выборке, а треть в — тестовой.  Классы в этом датасете обозначаются числами от 0 до 19.   
</p>

## Модель    

* Модель мешка слов       
* Логистическая регрессия       

<p align="justify">
Мы  преобразуем исходный текст в токены, затем построим словарь и взвесим токены. Реализуем модель мешка слов, разреженную векторную модель текста, затем мы реализуем логистическую регрессию на pytorch, обучим её, оценим её качество. А затем мы возьмём библиотеку scikit-learn (алгоритмы векторизации текстов из неё, а также реализацию логистической регрессии), обучим этот вариант модели и сравним с нашим вариантом. 
</p>    


##  Универсальные компоненты     

* Токенизация   
* Построение словаря    
* Фильтрация словаря   
* Построение матрицы   
* pytorch Dataset    
* цикл обучения и валидации    
* выбор лучшей модели в процессе обучения    
* оценка качества 

## Технологии
* [PyTorch](https://pytorch.org/)   
* [scikit-learn](https://scikit-learn.org/stable/index.html)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)
