### <img src="https://content.timeweb.com/assets/6fb683c0-4b13-4314-aae8-10938ede883e?width=1200&height=705" title="git" alt="git" width="300" height="150"/> 
 <h2>Git </h2>
<hr>
<h3>Команды Git, которые использовались для создания репозитория и выполнения задания, приведены ниже.</h3>
<h2>Задание 1</h2>
<table border="1">
  <tr><th>№</th><th>Команда</th><th>Описание</th></tr>
  <tr><td>1</td><td>Репозиторий создан удаленно<br>
  git@github.com:Dzianis-Brahinets/Dzianis-Brahinets.git </td><td>Создать свой репозиторий с таким же именем, как и имя пользователя</td></tr>
  <tr><td>2</td><td>$ git clone git@github.com:Dzianis-Brahinets/Dzianis-Brahinets.git</td><td>Склонировать его на свой компьютер в отдельную папку</td></tr>
  <tr><td>3</td><td>$ git clone git@github.com:testrusau/testrusau.git </td><td>Склонировать репозиторий в отдельную папку https://github.com/testrusau/testrusau</td></tr>
  <tr><td>4.1</td><td>$ cp testrusau/readme.md /d/Learning/Repository/Dzianis-Brahinets</td><td>Скопировать данные из склонированного репозитория и вставить их в свой репозиторий</td></tr>
  <tr><td>4.2</td><td>$ git add .</td><td>Добавить файла в индекс Git</td></tr>
  <tr><td>4.3</td><td>$ git commit -m "Фиксация данных"</td><td>Создать коммит</td></tr>
  <tr><td>4.4</td><td>$ git push  origin main</td><td>Отправить локальные коммитов в удаленный репозиторий</td></tr>
  <tr><td>4.5</td><td>$ rm -rf testrusau</td><td>Удалить склонированные данные из testrusau</td></tr>
  <tr><td>5.1</td><td>$ git add .</td><td>Открыть файл README.md и поочередно заменить каждый блок на необходимую информацию.<br>Сохранить изменения.<br>Добавить файл в индекс Git
  </td></tr>
  <tr><td>5.2</td><td>$ git commit -m "зафиксированные изменения"</td><td>Создать коммит</td></tr>
  <tr><td>5.3</td><td>$ git push</td><td>Отправить локальные коммитов в удаленный репозиторий</td></tr>
  </table>
<h2>Задание 2</h2>
<table border="1">
  <tr><th>№</th><th>Команда</th><th>Описание</th></tr>
  <tr><td>1</td><td>$ git init "Web Testing"</td><td> Создание репозитория локально на компьютере</td></tr>
  <tr><td>2</td><td>git@github.com:Dzianis-Brahinets/Web-Testing.git</td><td> Объявление репозитория удаленно</td></tr>
  <tr><td>3</td><td>$ cd "Web Testing"</td><td>Перейти в папку репозитория</td></tr>
  <tr><td>4</td><td>$ touch README.md</td><td>Создание файла Readme.md</td></tr>
  <tr><td>5</td><td>$ git add README.md</td><td>Добавление файла в индекс Git</td></tr>
  <tr><td>6</td><td>$ git commit -m "Create Readme"</td><td>Создание коммита</td></tr>
  <tr><td>7</td><td>$ git branch -M main</td><td>Переименование ветки с Master в Main</td></tr>
  <tr><td>8</td><td>$ git remote add origin git@github.com:Dzianis-Brahinets/Web-Testing.git</td><td>Добавление удаленного репозитория</td></tr>
  <tr><td>9</td><td>$ git push -u origin main</td><td>Отправка локальных коммитов в удаленный репозиторий</td></tr>
  </table>



