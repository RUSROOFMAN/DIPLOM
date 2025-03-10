# План по проверке и автоматизации приложения

### Описание приложения

Приложение предоставляет функционал по работе с новостями хосписа и включает в себя:
- Тематические цитаты;
- Информацию о приложении.
- Информацию о новостях и функционал взаимодействия с ними;

### Функционал приложения

1. Страница Autorization
- Поле ввода **"Login"**
- Поле ввода **"Password"**
- Кнопка **"SIGN IN"**

2. Страница Main
- Основное меню (Main, News, About)
- Вкладка **"Love is all"** с цитатами
- Кнопка профиля с возможностью выйти из него
- Вкладка с выподающим списком News с последними новостями

3. Вкладка меню News
- Сортировка новостей
- Применение фильтра (по дате, по категории)
- Возможность создания, удаления и редактирования новостей

### Виды тестирования
1. Функциональное тестирование;
2. UX/UI тестирование;
3. Тестирование совместимости;
4. Тестирование безопасности;
5. Теслирование локализации;
6. Стрессовое тестирование;

### Проверка приложения включает в себя:

1. Страница Авторизации:
    - Отображение всех элементов на странице;
    - Вход авторизованного пользователя;
    - Вход с невалидными данными;
    - Пустые поля Логин и Пароль.
      
2. Главный экран:
   - Отображение всех элементов на экране;
   - Отображение блока новостей;
   - Сворачивание/разворачивание блока новостей
   - Переход на другие страницы;
   - Выход из профиля.
     
3. Проверка экрана "Тематические цитаты":
   - Проверка элементов отображения;
   - Сворачивание/разворачивание отдельной цитаты.
     
4. Новостная страница:
    - Отображение элементов на экране;
    - Переход на экран "Панель управления";
    - Создание новости;
    - Удаление новости;
    - Редактирование новости;
      
6. Проверка экрана "О приложение":
   - Проверка отображения элементов на экране;
   - Открытие ссылки "Права пользования";
   - Открытие ссылки "Права конфиденциальности".

### Список инструментов

1. **_Android Studio_** -  среда разработки, которая используется для создания приложений для Android-устройств

2. **_Java_** - язык программирования

3. **_Espresso_** - тестовый фреймворк с открытым исходным кодом, интегрированный в Android Studio.

4.  **_Allure_** - фреймворк для создания простых и понятных отчётов автотестов

### Тестовая документация на проекте:
1. В проекте отсутствует документация по требованиям. Исходя из этого - применяется метод исследовательского тестирования.
2. При написании чек-листа, тест кейсов и автотестов была использована документация от компании Нетология, полученная во время обучения.

### Перечень необходимых специалистов для автоматизации:
- Руководитель проекта — отвечает за планирование, координацию и контроль процесса автоматизации тестирования, а также за управление рисками и ресурсами проекта (В нашем случае дипломный руководитель);
- Тестировщики — специалисты, которые разрабатывают тестовые сценарии и проверяют функциональность системы вручную;
- Автоматизаторы тестирования — эксперты, специализирующиеся на написании и поддержке автоматических тестов (В нашем случае его функцию выполняет тестировщик);
- Разработчики — создают и поддерживают автоматизированные тесты, интегрируя их с основной системой и обеспечивая совместимость с различными технологиями и платформами (В нашем случае его функцию выполняет тестировщик);
- Технические писатели — разрабатывают документацию для автоматизированных тестов, включая руководства пользователя, инструкции по установке и настройке инструментов автоматизации, а также рекомендации по использованию тестов (В нашем случае его функцию выполняет тестировщик).

### Окружение
- Эмулятор: Pixel 4 API 29
- Версия Android: 10.0
- Память телефона: 8gb
- Разрешение: 1080x2400
  
### Риски
1. Отсутствие технической документации;
2. Риск неработающего заявленного функционала приложения.
3. Неполное покрытие тестами негативных сценариев;
4. Технические неполадки.

### Интервальная оценка с учётом рисков:
- Время для ручного тестирования составляет 2-2.5 часа, 
- Время необходимое для автоматизации составляет 100 часов, с учетом рисков - 150 часов.

### План сдачи

1. Составление плана тестирования, создание чек-листа, создание тест-кейсов до 17.02.2025
2. Настройка окружения, написание, и отладка автотестов до 25.02.2025
3. Подготовка отчётных документов  до 28.02.2025
