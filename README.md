

Этот репозиторий содержит простой интерпретатор команд, написанный на языке C. Он поддерживает два базовых команды:

* **off**: Завершает работу программы.
* **ver**: Выводит версию программы.

Использование:

1. Скомпилируйте код с помощью C-компилятора, например, GCC:

   ```bash
   gcc main.c -o mycommand
   ```

2. Запустите исполняемый файл:

   ```bash
   ./mycommand
   ```

3. Программа запросит ввод:

   ```
   Код: 
   ```

4. Введите команду (off или ver) и нажмите Enter.

5. Программа выполнит команду и выведет соответствующий вывод.

Пример:

```
Код: ver
infinite code 1.3

Код: off
```

> Программа работает следующим образом:
>
> 1. Она запрашивает ввод пользователя.
> 2. Она сравнивает ввод с известными командами.
> 3. Если ввод соответствует известной команде, программа выполняет команду.
> 4. Если ввод не соответствует известной команде, программа выводит сообщение об ошибке.
