OTUS «Администратор Linux. Professional»
Урок 2.Vagrant

Задание: 
Обновеление ядра Linux на целевом хосте. 
Для выполнения задания использовался Debian 12.

Версия ядра назначается администратором. Перезагрузка машины происходит после успешного выполнения обновления ядра системы и загрузчика.
Запуск плейбука:
  ansible-playbook kernel_update.yml -K (Требуется пароль от root)