# Decoder
Ермолин Алексей Курсовой проект

Данный проект представляет собой Web-приложение, созданное с помощью технологии ASP NET Razor.

Проект позволяет проводить дешифроку и шифрование данных с помощью шифра Виженера.

При запуске данного приложения откроется вкладка "Главная", где кратко будет дана информация о проекте. Для того, чтобы перейти в меню дешифровки или шифровки, необходимо перейти в соответствующее меню посредством нажатия на кнопку в навигационном меню, находящейся в верхней части веб-приложения.

Декодировщик открывается путем нажатия на кнопку "Декодировать информацию". Декодировщик позволяет считать файл формата .txt, содержимое которого перенесется на текстовую зону "Текст для дешифровки". Содержание текста можно поменять по своему усмотрению. Вносить файл для корректной работы декодировщика не обязательно. Декодирование всегда будет происходить по ключу, данному в условии.  Дешифровка текста произойдет после нажатия на кнопку "Дешифровать". Результат дешифровки будет показан в текстовой зоне "Дешифрованный текст". Также результат можно сохранить в .txt файл, название которого выбирает пользователем путем введения его в соответствующее поле и сохранение изменений. Сохранение происходит в папку, в которую сохраняются все загружаемые браузером документы. Для её изменения необходимо изменить настройки браузера.

Кодировщик открывается путем нажатия на кнопку "Зашифровать информацию". Декодировщик позволяет считать файл формата .docx, содержимое которого перенесется на текстовую зону "Текст для шифрования". Содержание текста можно поменять по своему усмотрению. Вносить файл для корректной работы кодировщика не обязательно. Кодирование будет происходить по ключу, введенному пользователем. Для удобства текущий ключ отображается на сайте. Шифрование текста произойдет после нажатия на кнопку "Зашифровать". Результат шифровки будет показан в текстовой зоне "Дешифрованный текст". Также результат можно сохранить в .docx файл, название которого выбирает пользователем путем введения его в соответствующее поле и сохранение изменений. Сохранение происходит в папку, в которую сохраняются все загружаемые браузером документы. Для её изменения необходимо изменить настройки браузера.

Для создания проекта были задействованы библиотека Razor для удобного создания POST запросов и работы с веб-страницамИ, а также NPOI для работы с docx файлами.

Проект разработан Алексеем Ермолиным.
