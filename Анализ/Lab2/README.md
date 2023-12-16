# Этап 1. Выбор и обоснование средств проектирования и реализации  

Чтобы реализовать рекомендательную систему будем использовать библиотеку языка Python Surprise, созданную специально для решения этой задачи. Так же использование Python упрощает взаимодействие с другими частями проекта.

# Этап 2. Проектирование архитектуры приложения  

Рекомендательные системы относятся к классу алгоритмов, где обучение происходит "без учителя", и решают задачу кластеризации.  
Для создания модели необходимо определить несколько параметров, таких как модель алгоритма и метрика оценки.
SVD (сингулярное разложении матриц) - классический алгоритм для обучения рекомендательных систем. 

# Этап 3. Проектирование хранилища данных  

На рисунке представлена логическая модель базы данных для всего сервиса. 

![Логическая модель БД](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/db_model.jpg)

# Этап 4. Проектирование пользовательского интерфейса  

![Главный экран](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_greetings.png)
![Данной книги ещё нет в БД](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_search_results_null.png)
![Добавление книги](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_add_book.png)
![Результаты поиска](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_search_results.png)
![Меню действий](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_search_results_actions.png)
![Добавление оценки](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_review_window.png)
![Полная форма оценки](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_book_rate.png)
![Книги пользователя](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_my_books.png)
![Полная информация о книгах пользователя](https://github.com/malivasileva/book-recommendation/blob/main/Анализ/img/interface/Desktop_my_books_full.png)
