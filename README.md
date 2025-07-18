# 🔐 Autenticação com Node.js, MongoDB, JWT e Bcrypt

Este projeto é uma API de autenticação simples desenvolvida com **Node.js** e **Express**, utilizando **MongoDB** para persistência de dados, **Mongoose** como ODM, **bcrypt** para hash de senhas e **JWT (JSON Web Tokens)** para autenticação baseada em tokens.

## 🚀 Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Mongoose
- Bcrypt
- JSON Web Token (JWT)
- Dotenv

🔐 Segurança
Senhas são criptografadas com bcrypt antes de serem salvas no banco.

Tokens são gerados e verificados com JWT.

Rota protegida usa middleware para verificar se o token é válido.

✅ Requisitos
Node.js LTS

MongoDB local ou Atlas

📌 Observações

Este projeto é um ponto de partida para implementar autenticação nesta APIs. Irei expandir com:

Refresh Tokens 
Expiração de tokens
Regras de roles e permissões
Integração com front-end (React, por exemplo)
