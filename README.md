Используя 2 API составляются отчёты по всем пользователям в отдельных текстовых файлах.
После запуска скрипта, рядом создаётся директория с текстовыми файлами. Файл называется по username пользователя в формате "Antonette.txt".
Внутри файла на первой строке пишется полное имя, и рядом в <> записывается email. Через пробел от email записывается время составления отчёта в формате 23.09.2020 15:25.
На второй строке записывается название компании, в которой работает пользователь.
На четвёртой строке "Завершённые задачи:" и далее список названий завершённых задач.
После завершённых задач через пустую строку записываются "Оставшиеся задачи:" и выводятся остальные задачи.
Названия задач больше 50 символов, обрезаются до 50 символов и добавляется троеточие.
Если файл для пользователя уже существует, то существующий файл переименовывается, в название файла добавляется время составления старого отчёта в формате "Antonette_2020-09-2315:25.txt".
Таким образом, актуальный отчёт всегда будет без даты в названии. Старые отчёты не удаляются, а переименовываются.
