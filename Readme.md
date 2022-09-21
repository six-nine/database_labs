# Система такси
Козлов Вадим, гр. 053501

## Функциональные требования к проекту
### Роли пользователей
1. Администратор
2. Модератор
3. Водитель
4. Клиент

### Авторизация пользователя
Пользователь должнен иметь возможность:
- Зарегистрироваться с помощью электронной почты с процедурой подтверждения.
- Войти в аккаунт.
- Восстановить доступ (изменить пароль)

### Возможности пользователей
- Все пользователи
    + Просматривать информацию о своём профиле
    + Редактировать личную информацию
    + Удалить аккаунт
    + Вести чат с другими пользователями:
        * Водитель - Модератор
        * Водитель - Клиент
        * Клиент - Модератор

- Администратор
    + Подтвердить модератора
    + Снять модератора
    + Создать, просмотреть, отредактировать или удалить любого пользователя
- Модератор
    + Подтвердить/отклонить заявку на регистрацию водителя
    + Заблокировать аккаунт водителя/клиента
    + Добавить автомобиль в базу, удалить его, редактировать информацию
    + Назначить автомобиль водителю
    + Снять автомобиль с водителя
- Водитель
    + Подать заявку на подтверждение аккаунта (приложив необходимые документы)
    + Принять заказ
    + Отказаться от заказа
    + Начать чат с модератором
- Клиент
    + Создать заказ
    + Оценить поездку

### Таблицы
- Абстрактный пользователь
- Водитель
- Модератор
- Пользователь
- Администратор
- Автомобиль
- Документы водителя
- Заказ
- Чат
- Сообщение в чате
