Этот блог предоставляет возможность новым пользователям зарегистрироваться или авторизоваться. Авторизованные пользователи имеют доступ к своей личной странице, где могут создавать новые посты, отображаемые на главной странице блога. Они также могут оставлять комментарии к постам, которые сразу же публикуются.

Неавторизованные пользователи также могут комментировать посты, но им необходимо предоставить свой адрес электронной почты, и комментарии будут опубликованы после одобрения администратором.

Пользователи с правами администратора обладают возможностью удаления и изменения постов, а также одобрения и удаления комментариев.

Для развертывания блога выполните следующие шаги:

Установите PHP и добавьте его путь в переменные среды (Path).
Установите среду разработки, такую как PhpStorm, поддерживающую PHP.
Скачайте Symfony и добавьте его путь в переменные среды (Path).
Разверните Symfony в необходимой папке с помощью команды symfony new --webapp (название проекта), предварительно установив Git BASH для удобства.
Выберите базу данных (например, Open Server) для хранения информации о пользователях, комментариях и постах.
Создайте и укажите путь к базе данных в файле .env.
Выполните миграции с помощью команд: php bin/console make:migration и php bin/console doctrine:migrations:migrate (введите команды в терминале последовательно).