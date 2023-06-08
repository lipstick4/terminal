# terminal

1) Посмотреть где я
  Pwd

2) Создать папку
  mkdir 33group

3) Зайти в папку
  cd 33group

4) Создать 3 папки
  mkdir 1dir 2dir 3dir 

5) Зайти в любою папку
  cd 1dir 

6) Создать 5 файлов (3 txt, 2 json)
  cat > one.txt 
 cat > two.txt
 cat > tree.txt
 cat > one.json
 cat > two.json

7) Создать 3 папки
  mkdir onedir twodir threedir

8. Вывести список содержимого папки
  Ls

9) + Открыть любой txt файл
  cat one.txt


10) + написать туда что-нибудь, любой текст.
  vim one.txt

11) + сохранить и выйти.
  cat one.txt
  Hello,World!

12) Выйти из папки на уровень выше
  Cd ..

—
13) переместить любые 2 файла, которые вы создали, в любую другую папку.
mv two.txt 2dir/two.txt
mv tree.txt 2dir/tree.txt

14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
cp one.txt 3dir/one.txt
cp tree.txt 3dir/tree.txt

15) Найти файл по имени
find . -iname two.txt

16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
17) вывести несколько первых строк из текстового файла
head /Users/rabetskaya.viktoriya/33group/1dir/two.txt

18) вывести несколько последних строк из текстового файла
tail -n10 /Users/rabetskaya.viktoriya/33group/1dir/two.txt

19) просмотреть содержимое длинного файла (команда less) изучите как она работает.
less -s two.txt

20) вывести дату и время
date
Mon Feb  6 16:00:15 EET 2023
=========
