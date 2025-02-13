# ТЗ на сервис Secret

## Описание сервиса
Сервис предназначен для безопасного обмена текстовыми данными. Например это могут быть доступы к сайтам и прочее.

## Задание
Необходимо реализовать backend, frontend и api (api факультативно).

### Сценарий использования
*   Пользователь А в textarea размещает секретный контент. Защищает его паролем.
*   При сохранении контента пользователю А показывается ссылка вида [http://secret.arealidea.ru/fgh8b5](http://secret.arealidea.ru/fgh8b5). 
*   В сервисе сохраняется зашифрованный контент.
*   Контент становится доступным по короткой ссылке.
*   Пользователь А передает пользователю Б ссылку на контент на сервисе. 
*   Пользователь А передает пользователю Б пароль к контенту способом отличным от передачи ссылки. _Этот пункт реализовывать не нужно_
*   Пользователь Б заходит по ссылке. Вводит пароль от контента. Получает контент.

### Примечания
1. Ссылка должна быть:
*   уникальная;
*   автогенерируемая;
*   имеет вид: secret.arealidea.ru/fgh8b5;
*   размер не более 6 символов.
2. Информация должна сохраняться в БД и быть доступна для удаления пользователем, который знает пароль. Данные в БД должны быть зашифрованы.


## Стек технологий для выполнения задания

**Backend:** php или node.js

**Frontend:** на выбор.

Фреймворки и CMS по желанию.
