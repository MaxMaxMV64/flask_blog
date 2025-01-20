# flask_blog
Примеры использования API
Создание поста
Метод: POST
URL: /posts
Тело запроса:


{
    "title": "Мой первый пост",
    "content": "Привет всем! Это мой первый блог-пост.",
    "author": {
        "username": "admin"
    }
}
Ответ:


{
    "message": "Post created successfully!"
}
Обновление поста
Метод: PUT
URL: /posts/1
Тело запроса:


{
    "title": "Измененный заголовок",
    "content": "Это обновленный контент."
}
Ответ:


{
    "message": "Post 1 updated"
}
Удаление поста
Метод: DELETE
URL: /posts/1

Ответ:


{
    "message": "Post 1 deleted"
}
