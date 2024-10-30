# samba

Чтобы расшарить папку в Linux, можно использовать сервер Samba с использованием протокола SMB (CIFS):

**1. Установите Samba**, если он не установлен. В некоторых дистрибутивах установку можно указать в параметрах установщика. В большинстве дистрибутивов Samba устанавливается отдельно.  
**2. Настройте доступ в Samba без пароля** с помощью программы system-config-samba. Она есть во всех популярных дистрибутивах Linux.  
**3. Создайте общую папку**, которую хотите разделить с другими пользователями в сети. Правый клик по папке — выбрать «Параметры общего доступа». Переключить опцию «Общий доступ к этой папке» в положение «On».  
**4. Создайте учётные записи пользователей**, которым нужен доступ к общей папке. Откройте окно «Пользователи и группы», создайте нового пользователя, введите его имя и пароль, нажмите «Добавить». Повторите процесс для каждого пользователя, которому нужен доступ к общей папке.  
**5. Предоставьте пользователям доступ к общей папке**. Правый клик по общей папке — выбрать «Параметры общего доступа». Перейти на вкладку «Разрешения». Добавить нового пользователя, которому нужно предоставить доступ к папке.  
**6. Установите уровень доступа** для пользователя — «Чтение» или «Запись». Повторите процесс для каждого пользователя, которому нужен доступ к общей папке.  
**7. Перезапустите Samba**, чтобы изменения вступили в силу.   


[Как расшарить папку Linux без пароля](https://ru.d-ws.biz/articles/linux-share-files-samba.shtml)  
[How to easily share files and folders on a Linux Mint network](https://www.fosslinux.com/103443/how-to-easily-share-files-and-folders-on-a-linux-mint-network.htm)
