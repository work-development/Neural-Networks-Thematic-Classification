# Тематическая классификация текстов.         

<p align="justify">
Будим работать с датасетом для тематической классификации, "20 новостных групп", который состоит из примерно 20 тысяч сообщений электронной почты, распределенных по 20 категориям. Мы  преобразуем исходный текст в токены, затем построим словарь и взвесим токены. Реализуем модель мешка слов, разреженную векторную модель текста, затем мы реализуем логистическую регрессию на pytorch, обучим её, оценим её качество. А затем мы возьмём библиотеку scikit-learn (алгоритмы векторизации текстов из неё, а также реализацию логистической регрессии), обучим этот вариант модели и сравним с нашим вариантом. 
</p>

