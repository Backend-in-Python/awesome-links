<p align="center">
  <img width="400" height="400" src="https://user-images.githubusercontent.com/50069473/222978506-35c2fad2-aac5-4c44-b6a0-89601d4fd86f.png">
</p>

<h1 align="center">
    awesome-links

</h1>
<p align="center">
В этом репозитории я буду собирать различного рода ссылки на ресурсы, которые качественно передают суть темы.

</p>


## Навигация
- [Python](#python)
  * [Code Quality](#code-quality)
- [Машинное обучение](#машинное-обучение)
  * [Нейронные сети](#нейронные-сети)

## Python


### Architecture

* [Clean Architecture](https://www.cosmicpython.com/book/preface.html) - книга про реализацию чистой архитектуры на python;

### Code Quality

* [Radon](https://github.com/rubik/radon) - утилита для подсчета метрки сложности кода в python.

## Машинное обучение

### Нейронные сети
* [Why Neural Networks can learn (almost) anything ](https://youtu.be/0QczhVg5HaI)(Youtube) — рассказывает про основы нейронныех сетей через призму функций в математике. Хорошая визуализация, поясняющая, что из себя представляет нейронная сеть без углубления в математические дебри.
* [How to Create a Neural Network (and Train it to Identify Doodles)](https://youtu.be/hfMk-kjRv4c)(Youtube) — рассказывает про основы нейронныех сетей на примерах от простого к сложному. Хорошая визуализация в unity. Автор пытается вручную подобрать параметры сети, чтобы показать визуально, как меняется сети, а затем постепенно подходит к вопросу тренировки сети и применения математики. Из интересеного для себя почерпнул, что MNIST цифры можно визуализировать в виде данных о пикселях в 3д формате, а сама сетка должна понять координаты этих областей, чтобы правильно классифицировать цифры.



## DB


* [Что такое ACID](https://habr.com/ru/post/555920/) - простыми терминами объясняет, что такое ACID в контексте базы данных. 


## Backend

### Idempotency
* [An In-Depth Introduction To Idempotency](https://www.lpalmieri.com/posts/idempotency/) - статья про идемпотентность запросов(Rust). Пример на расте, но уловить концепции можно. В статье автор написал сервис рассылки имейлов. По кнопке пользователь отправляет запрос  на сервер, сервер его обрабатывает и шлет запрос к стороннему API имейлов.

* [Implementing Stripe-like Idempotency Keys in Postgres](https://brandur.org/idempotency-keys) - статья про идемпотентность запросов(Ruby).

