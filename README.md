# Тестовое задание
Тестовое задание для Frontend-разработчиков

## Описание
В результате выполнения задания, должны увидеть работоспособное приложение - менеджер задач.
Не стоит уделять много времени его стилизации, однако приложение должно выгляжеть приемлемо.

## Технологии
- React (только функциональные компоненты)
- React Hooks
- Redux
- Допускается использование Create React App
- Желательно использовать Typescript

Проект может разрабатываться как desktop (electron) или мобильное приложение (react native).

## Требования и задачи
- Необходимо добавить начальное окно с возможностью перейти на новое окно "События", по клику на кнопку
- При первичной загрузке окна "События" отображать несколько заданных по умолчанию. СОбытие должно содержать миимум два поля: дата и описание
- Реализовать добавление нового события:
  * Дата события - текущая + 1 неделя (генерируется автоматически)
  * Текст события - максимальная длина 120 символов
- Добавить кнопку, при клике по которой очищаются все события в списке
- Если описание события не помещается в границы экрана, обрезаем его многоточием
- События, дата которых уже прошла, выделить цветом (например: красная заливка)

## Отправка на проверку

1. Создать репозиторий на github
2. Залейте проект и отправьте ссылку как отклик на вакансию и на alg@trusted.ru
