<!-- <p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

In addition, [Laracasts](https://laracasts.com) contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

You can also watch bite-sized lessons with real-world projects on [Laravel Learn](https://laravel.com/learn), where you will be guided through building a Laravel application from scratch while learning PHP fundamentals.

## Agentic Development

Laravel's predictable structure and conventions make it ideal for AI coding agents like Claude Code, Cursor, and GitHub Copilot. Install [Laravel Boost](https://laravel.com/docs/ai) to supercharge your AI workflow:

```bash
composer require laravel/boost --dev

php artisan boost:install
```

Boost provides your agent 15+ tools and skills that help agents build Laravel applications while following best practices.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT). -->



<!-- Descrição do projeto: -->

# 🐦 Clone do Twitter com Laravel (Plumage)

## 📌 Sobre o projeto

Este projeto é um clone simplificado do Twitter (X), desenvolvido utilizando o framework Laravel, com foco em aprendizado prático dos conceitos fundamentais do desenvolvimento web moderno.

A aplicação permite que usuários se autentiquem, criem publicações (tweets) e visualizem um feed com conteúdos, simulando o comportamento básico de uma rede social.

---

## 🎯 Objetivo do projeto

O principal objetivo foi aplicar, na prática, os conceitos ensinados na documentação oficial do Laravel, construindo uma aplicação completa com:

- Backend estruturado com MVC  
- Sistema de autenticação  
- Integração com banco de dados  
- Funcionalidades reais de uma rede social  

---

## 🧠 Principais aprendizados

Durante o desenvolvimento deste projeto, foram consolidados conhecimentos importantes:

### 🔹 Estrutura MVC (Model-View-Controller)
- Separação clara de responsabilidades
- Organização escalável do código

### 🔹 Rotas
- Mapeamento de URLs para ações da aplicação
- Uso de rotas protegidas com autenticação

### 🔹 Controllers
- Centralização da lógica da aplicação
- Manipulação de requisições e respostas

### 🔹 Eloquent ORM
- Abstração do banco de dados
- Manipulação de dados com modelos

### 🔹 Relacionamentos
- Relação entre usuários e posts
- Uso de `hasMany` e `belongsTo`

### 🔹 Autenticação
- Registro e login de usuários
- Controle de acesso com middleware

### 🔹 Migrations
- Criação e versionamento do banco de dados

---

## ⚙️ Funcionalidades

### 👤 Usuários
- Cadastro de conta
- Login e logout
- Sessões autenticadas

### 📝 Tweets (Posts)
- Criação de posts
- Listagem de posts no feed
- Associação de posts com usuários

### 📰 Feed
- Exibição de posts em ordem cronológica
- Carregamento dinâmico via banco de dados

---

<!--## 🏗️ Estrutura do projeto

```bash
app/
 ├── Models/
 │    ├── User.php
 │    ├── Post.php
 │
 ├── Http/
 │    ├── Controllers/
 │         ├── PostController.php

routes/
 ├── web.php

resources/
 ├── views/
 │    ├── posts/
 │    ├── layouts/

database/
 ├── migrations/ -->
