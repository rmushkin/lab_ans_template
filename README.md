# Шаблон репозитория-отчёта
## С чего начать:
1. Использовать этот репозиторий как шаблон:

   ![изображение](https://github.com/user-attachments/assets/33af80f5-64df-4445-b5b7-81497d0d99ac)
3. Переименовать во что-то подходящее:

   ![изображение](https://github.com/user-attachments/assets/fdd74b3b-aefd-4947-9e28-95ecf069da2c)

## Первоначальная загрузка работы 

1. Создать новый файлы...

   ![изображение](https://github.com/user-attachments/assets/783b7be4-5dda-4d79-be9a-5a2543b0dc4c)
  3. Загрузив папку:

     ![изображение](https://github.com/user-attachments/assets/a20cf094-d801-439c-9382-96961ffd500d)
  4. Или создав файлы по одному прямо в веб-интерфейсе GitHub (чтобы создать промежуточные папки, нужно вводить "/" посдле каждого имени папки):

     ![изображение](https://github.com/user-attachments/assets/de611c1b-dec9-4bc8-b057-0186680fadb9)

2. ...И зафиксировать их создание **в новой ветке**, одновременно открыв запрос на её слияние с основной.

   - "Commit message" - это короткое объяснение того, что вы сделали (для чтения людьми). Можно оставить значение по умолчанию.
   - "branch name" - это имя ветки, которая будет создана под ваши изменения. Лучше использовать латиницу, можно оставить значение по умолчанию.

   ![изображение](https://github.com/user-attachments/assets/7fc95a68-4048-473e-aa38-8797e8dcb830)

 3. Не забыть создать пулл-реквест:

    ![изображение](https://github.com/user-attachments/assets/f6727a58-0ad1-40dd-9ee4-d90b747c5d4a)

 4. Дождаться автоматической проверки...

    ![изображение](https://github.com/user-attachments/assets/64ddccee-4f57-447c-b93a-21e053d145fb)

    - В случае провала - см. "[Повторная загрузка решений](#%D0%BF%D0%BE%D0%B2%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B0-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B9)":
    
      ![изображение](https://github.com/user-attachments/assets/858bd55c-e992-441e-8823-c24f4cf9ceae)

    - В случае успеха - ссылку на пулл-реквест (именно на него!) нужно скопировать в поле ответа СДО.

## Повторная загрузка решений

❗ Выполняется в ту же ветку, что и первоначальная загрузка!

1. Выбрать ветку, в которую было загружено непринятое решение:

   ![изображение](https://github.com/user-attachments/assets/9ea21d17-0284-468d-8e67-e82c2fe8a127)


2. Повторно загрузить или напрямую отрежактировать нужный файл
3. На этот раз закоммитить **напрямую** в целевую (не `main`!) ветку:

   ![изображение](https://github.com/user-attachments/assets/161c9111-4ef5-439e-a699-f50c4f723398)
4. Дождаться автопроверки, а затем - проверки преподавателем.
