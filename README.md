# Terminal
1) Посмотреть где я : pwd
2) Создать папку: mkdir Terminal
3) Зайти в папку : cd Terminal
4) Создать 3 папки: mkdir den1 den2 den3
5) Зайти в любую папку: cd den1
6) Создать 5 файлов (3 txt, 2 json):  touch 1.txt 2.txt 3.txt 1.json 2.json
7) Создать 3 папки mkdir folder1 folder2 folder3
8. Вывести список содержимого папки:  ls -la
9) + Открыть любой txt файл : cat 1.txt
10) + написать туда что-нибудь, любой текст: vim den1/1.txt
11) + сохранить и выйти:  :wq
12) Выйти из папки на уровень выше: cd ..
—
13) переместить любые 2 файла, которые вы создали, в любую другую папку: 
mv den1/1.txt den1/2.txt den2

14) скопировать любые 2 файла, которые вы создали, в любую другую папку: 
       cp den2/1.txt den2/2.txt den3

15) Найти файл по имени:
find -name 1.json
./den1/1.json

16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
tail -F den2/1.txt | grep Good morning den2/1.txt

17) вывести несколько первых строк из текстового файла: head -2 den2/1.txt
18) вывести несколько последних строк из текстового файла:  tail -2 den2/1.txt

19) просмотреть содержимое длинного файла (команда less) изучите как она работает less den2/1.txt
20) вывести дату и время: date +"%D %T"
=========

Задание *
1) Отправить http запрос на сервер: curl http://162.55.220.72:5006/terminal-hw-request
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

cd /d/Terminal;\
> mkdir den_0 den_1 den_2;\
> cd den_0;\
> touch file1.txt file2.txt file3.txt file4.json file5.json;\
> mkdir den_4 den_5 den_6;\
> ls -la;\
> mv file1.txt file4.json /d/Terminal/den_1

