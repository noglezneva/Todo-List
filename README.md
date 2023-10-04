# Todo-List
Эта программа представляет собой простое веб-приложение, которое обслуживает веб-страницу списка дел (ToDo list).

Оператор import импортирует три пакета: html/template, log и net/http.

Программа определяет две структуры: Todo и PageData. Todo представляет собой отдельный элемент списка дел, а PageData представляет данные, которые будут переданы в HTML-шаблон.

Функция todo является обработчиком, который генерирует данные списка дел и передает их в HTML-шаблон. Функция main настраивает новый HTTP-сервер, регистрирует функцию todo для обработки запросов к конечной точке /todo и обслуживает статические файлы из каталога static.

HTML-шаблон определяет структуру веб-страницы списка дел. Он использует структуру PageData для заполнения страницы элементами списка. Код JavaScript в конце HTML-файла добавляет слушатель событий к каждому элементу списка, переключая его класс между done и not done при щелчке.
