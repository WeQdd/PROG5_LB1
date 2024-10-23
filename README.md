# ЛБ1. Реализация удаленного импорта собственного пакета.
1. **Создать файл myremotemodule.py, для импорта. Расположим его в директорию rootserver.**
   ![myremotemodule.py](https://github.com/user-attachments/assets/83a9146b-7617-4736-94f2-ad61790808d4)

2. **Создать файл activation_script.py, который содержит в себе функции url_hook, классы URLLoader и URLFinder из конспекта.**
   ![activation_script.py](https://github.com/user-attachments/assets/f18e5df6-47fd-4ca1-b689-0d741ddcc56b)

3. **Запустим http сервер для удаленного импорта. Для этого пропишем *python -m http.server* в директории c файлом myremotemodule.py**
   ![Консоль](https://github.com/user-attachments/assets/80aba734-33f7-41dc-aad9-b650c6e14430)

4. **Теперь запустим интерактивное представление файла *activation_script.py* - *python -i activation_script.py* и получим вывод функции *myfoo* из файла myremotemodule.py**
   ![Консоль](https://github.com/user-attachments/assets/3b666508-91fa-4510-b611-230582bb5ff7)
