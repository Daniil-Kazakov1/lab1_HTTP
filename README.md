# lab1_HTTP
Создание системы авторизации пользователей на протоколе HTTP
## Постановка задачи 
Спроектировать и разработать систему авторизации пользователей на протоколе HTTP
## Ход работы 
 -Создание пользовательского интерфейса и описание сценариев работы
 
 ![рис.1:Интрефейс](https://github.com/Daniil-Kazakov1/lab1_HTTP/blob/main/интерфейс.png)

Изначально открывается страница входа (sign-in.php).Пользователь может ввести логин и пароль и зайти в свой аккаунт, нажав кнопку "Войти". В случае корректного ввода данных открывается главная страница (index.php) с приветсвием "Привет, <name>".
 В случае некорректного ввода: 
 1)Если введен неправильный логин - возврат на страницу вход и вывод сообщения "Такого пользователя нет в системе".
 2)Если введен неправильный парол - возврат на страницу вход и вывод сообщения "Неверный пароль".
 Если пользователь не имеет аккаунта, он может перейти на форму регистрации, нажав кнопку "Зарегестрироваться". Полсе этого откроется страница регистрации (registration.php). Далее необходимо ввести данные: имя, логин, пароль и подтверждение пароля. В случае корректного ввода данных открывается главная страница (index.php) с приветсвием "Привет, <name>". В случае некорректного ввода пользователь возвращается на страницу регистрации, где будет выведено сообщение об ошибки.
