# Критерии приема
1. Создан репозиторий goit-js-hw-11.
2. При сдаче домашней работы есть две ссылки: на исходные файлы и рабочую страницу на GitHub Pages.
3. При посещении живой страницы задания, в консоли нету ошибок и предупреждений.
4. Проект собран с помощью parcel-project-template.
5. Для HTTP запросов использована библиотека axios.
6. Используется синтаксис async/await.
7. Для уведомлений использована библиотека notiflix.
8. Код отформатирован Prettier.

## Задание - поиск изображений
Создай фронтенд часть приложения поиска и просмотра изображений по ключевому слову. Добавь оформление элементов интерфейса. Посмотри демо видео работы приложения.

## Форма поиска
Форма изначально есть в HTML документе. Пользователь будет вводить строку для поиска в текстовое поле, а при сабмите формы необходимо выполнять HTTP-запрос.

<form class="search-form" id="search-form">
  <input
    type="text"
    name="searchQuery"
    autocomplete="off"
    placeholder="Search images..."
  />
  <button type="submit">Search</button>
</form>
