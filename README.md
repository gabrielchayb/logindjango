Sistema de Login

Este projeto é um sistema de login simples utilizando Django como framework backend e PostgreSQL como banco de dados. Ele oferece funcionalidades de autenticação como login, registro e logout por meio de APIs.

Stack Utilizada

	•	Backend: Django 4.2.x
	•	Banco de Dados: PostgreSQL
	•	APIs: Django Rest Framework (DRF)
	•	Autenticação: Django Rest Framework Token Authentication

Endpoints da API

As APIs de login foram desenvolvidas utilizando Django Rest Framework com autenticação por token. Abaixo está um resumo dos principais endpoints e como consumi-los:

Endpoints

	•	POST /api/auth/register/ — Registra um novo usuário.
	•	POST /api/auth/login/ — Autentica o usuário e retorna um token.
	•	POST /api/auth/logout/ — Faz o logout do usuário autenticado.

