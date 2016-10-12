На сайт без установленных вручную модулей (чистый)

1. Установить и включить модули: Chaos tools, Views, Features, rn-page (в Модулях будет виден как List users).
2. Из архива list_of_users_feature-7.x-1.0 установить и включить модуль list_of_users_feature.
   После включения этого модуля:
	- станут доступны пути: /drupal-test-task, /drupal-test-task-views
	- при обращении по пути: drupal-test-task-views - отобразится таблица с пользователями системы (колонки: id, username и ссылка на редактирование) 
	  используя модуль Views
	- при обращении по пути: drupal-test-task       - отобразится таблица с пользователями системы (колонки: id, username и ссылка на редактирование) 
	  используя самописный модуль rn-page (List users) который использует API Drupal (#theme => table)
	
Отладочный домен: http://123mastera.ru
Администратор логин: admin, пароль: nimda.
ftp://123mastera.ru/
login: dimbra_mastera
password: 7ims0t140
