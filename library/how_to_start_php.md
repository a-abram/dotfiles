# Как выполнить PHP код на своем компьютере

1. Скачайте и установите [denwer](http://www.denwer.ru/). Это настроенная сборка `apache` (веб сервер) + `MySQL` (база данных) + какой-то `почтовый сервер`.  
    При установке везде жмите да (возможно, вы согласитесь продать душу, но зато читать ничего не надо).  
2. Выпейте чаю.
3. После успешной установки у вас на рабочем столе появится 3 ярлыка: для запуска, остановки и перезагрузки сервера.  
4. Клацаете на ярлык `start`, после чего у вас примонтируется диск с той буквой, которую вы указали во время установки.  
    Откройте папку `Буква диска:\home`. В этой папке находится еще N каталогов. Если вбить название любого из них в адрессную строку браузера, откроется сайт, находящийся в данной папке. Поэтому откройте `Буква диска:\home\localhost\` и ~все удалите оттуда~ поместите свои php скрипты в нее.  
    Должно было все заработать. Если что-то пошло не так, выполните пунк **2** и перезагрузите сервер.  