# geekmo-gui

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


«общая карта» поддерживаемых адресов и запросов

<table>
    <thead>
        <tr>
            <th>Адрес</th>
            <th colspan=2>GET</th>
            <th colspan=2>POST</th>
            <th colspan=2>PUT</th>
            <th colspan=2>DELETE</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>/auth</td>
            <td>Инфо о пользователе</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Авторизоваться на сервере</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Завершить текущий сеанс</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/server_info</td>
            <td>Инфо о сервере</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/projects</td>
            <td>Список геологических проектов</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/projects<br>~/tech</td>
            <td>Список технологических проектов</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/projects<br>~/newproject</td>
            <td></td>
            <td></td>
            <td>Создать новый геологический проект</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/project/{PID}</td>
            <td>Инфо о геологическом проекте</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Задать параметры геологического проекта или переименовать его</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить геологический проект</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/project/{PID}<br>\~/tech</td>
            <td>Получить параметры технологического проекта</td>
            <td><input type="checkbox" disabled /></td>
            <td></td>
            <td></td>
            <td>Задать параметры геологического проекта, соответствующие технологическому</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/project/{PID}<br>~/newtable</td>
            <td></td>
            <td></td>
            <td>Создать новую таблицу</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/project/{PID}<br>~/newcolumn</td>
            <td></td>
            <td></td>
            <td>Создать новую колонку проекта</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/project/{PID}<br>~/column/{CID}</td>
            <td>Инфо о колонке проекта</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Изменить параметры колонки проекта или переименовать ее</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить колонку проекта</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/project/{PID}<br>~/column/{CID}<br>\~~/clear</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Очистить колонку проекта от данных</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}</td>
            <td>Инфо о таблице с данными</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Изменить параметры таблицы или переименовать ее</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить таблицу</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/clear</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Очистить данные таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/newtable</td>
            <td></td>
            <td></td>
            <td>Создать новую дочернюю таблицу</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/newcolumn</td>
            <td></td>
            <td></td>
            <td>Создать новую колонку таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}</td>
            <td>Инфо о колонке таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Изменить параметры колонки таблицы или переименовать ее</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить колонку таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}<br>\~~/clear</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Очистить колонку таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}<br>\~~/newitem</td>
            <td></td>
            <td></td>
            <td>Создать новый элемент списка для списковой характеристики</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}<br>\~~/item/{NUM}</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Изменить элемент списка</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить элемент списка</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}<br>\~~/condition</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Задать параметры кондиции для расчета</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/column/{CID}<br>\~~/refresh</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Пересчитать колонку с формулами или кондицией</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/data/{FORMAT}</td>
            <td>Получить данные таблицы</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/newline</td>
            <td></td>
            <td></td>
            <td>Создать новую строку данных</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/data/{PK}</td>
            <td>Получить строку данных</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Изменить строку данных</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить строку данных</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/multidata</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Изменить несколько строк данных</td>
            <td></td>
            <td>Удалить несколько строк данных</td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/check</td>
            <td></td>
            <td></td>
            <td>Запустить проверку</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/table/{TID}<br>~/export</td>
            <td></td>
            <td></td>
            <td>Экспортировать данные таблицы в файл</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/uploads</td>
            <td>Список загруженных на сервер файлов</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Удалить все загруженные на сервер файлы</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/uploads<br>~/newfile</td>
            <td></td>
            <td></td>
            <td>Загрузить файл на сервер</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/file/{FID}</td>
            <td>Инфо о загруженном файле</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>Удалить загруженный файл</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
        <tr>
            <td>/file/{FID}<br>~/raw</td>
            <td>Предросмотр данных файла в сыром виде</td>
            <td></td>
            <td>Предпросмотр данных файла с учетом разделителей и кодировки</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/file<br>~/import</td>
            <td></td>
            <td></td>
            <td>Импортировать данные файла в таблицу</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Исправить связи строк дочерней таблицы со строками родительской таблицы на основании названия колонок</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/tables</td>
            <td></td>
            <td></td>
            <td>Получить список таблиц ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/table</td>
            <td></td>
            <td></td>
            <td>Инфо о таблице ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/table<br>~/raw/{FORMAT}</td>
            <td></td>
            <td></td>
            <td>Предпросмотр сырых данных таблицы ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/import</td>
            <td></td>
            <td></td>
            <td>Импортироваить данные из таблицы ODBC в таблицу</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc</td>
            <td>Cписок сценариев импорта ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/newscenario</td>
            <td></td>
            <td></td>
            <td>Новый сценарий импорта ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>/odbc<br>~/scenario/{sid}</td>
            <td>Получить сценарий импорта ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td></td>
            <td></td>
            <td>Изменить сценарий импорта ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
            <td>Удалить сценарий импорта ODBC</td>
            <td><input type="checkbox" disabled checked /></td>
        </tr>
    </tbody>
</table>

<span style="color:red;"><input type="checkbox" disabled/> Не реализовано</span>

<span style="color:darkgreen;"><input type="checkbox" disabled checked /> Реализовано и покрыто тестами</span>

