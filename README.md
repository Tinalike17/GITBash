<h2 align="center">GITBash - Homework_1</h2>

   |Task   |     Answer|
| ---------------------    | ----------------------------|
| 1. Подивитися де я |       `pwd`|
| 2. Створити папку  |      `mkdir dr_git_bash_1`|
| 3. Перейти до папки |     `cd dr_git_bash_1`|
| 4. Створити 3 папки |     `mkdir dr_2 dr_3 dr_4`|
| 5. Перейти у будь-яку папку |    `cd dr_3`|
| 6. Створити 5 файлів (3 txt, 2 json) |    `touch english.txt italian_grammar.txt italian_vocab.txt english_vocab.json italian_vocab.json`|
| 7. Створити 3 папки |                     `mkdir new_dr_0 new_dr_1 new_dr_2`|
| 8. Вивести список вмісту папки |    `ls`|
| 9. Відкрити будь-який txt файл |    `vim italian_vocab.txt`|
| 10. Написати туди що-небудь |     `click on "I" to go to edit mode then write smth like (Prego - You are welcome/Don't mention it)`|
| 11. Зберегти і вийти|             `click on "Esc" to exit insert mode, then type ":wq" or ":x" to save and exit`|
| 12. Вийти із папки на рівень вище |  `cd ..`|
| 13. Перемістити будь-які 2 файла, які були створені, в будь-яку іншу папку |  `mv dr_3/*.json dr_2 - The command moves all files(there are only 2 files) with .json extension to dr_2 (Location before the mv command is dr_git_bash_1 directory)`|
| 14. Скопіювати будь-які 2 файла, які були створені, в будь-яку іншу папку |  `cp dr_3/italian_grammar.txt dr_4   cp dr_3/italian_vocab.txt dr_4` (cp followed by the name of the file you want to copy and the name of the directory to, where you want to copy the file)|
| 15. Знайти файл за іменем |   `find . -name 'e*' ` - Output: `./dr_2/english_vocab.json   ./dr_3/english.txt` (This command searches for the file which name starts with an e, and (it searches for the file in all directories - .) ) |
| 16. Переглянути вміст у реальному часі (команда grep) вивчіть, як вона працює.| `tail -f italian_vocab.txt` - Output: 1. Prego - You are welcome/Don't mention it  2. A dopo - See you later 3. Bounasera - Good evening 4. Arriverderci - Goodbye 5. Grazie mille - Thanks a lot (Ctrl+C to exit) | 
