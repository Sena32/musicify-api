<div align="center">

# 🎵 **Musicify API**

**RESTful API built for study purposes and CRUD practice using Java and Spring Boot.**

[![Status](https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge)]()
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)]()
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)]()
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)]()
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)]()

</div>

---

### 🧠 **Sobre o projeto**

A **Musicify API** é uma aplicação desenvolvida para estudo de CRUD, boas práticas REST e manipulação de dados com **Spring Boot**.  
Ela simula um sistema de gerenciamento de músicas, playlists, autores e comentários.

---

### ⚙️ **Funcionalidades**

- [x] CRUD de Usuários  
- [x] CRUD de Playlists  
- [x] CRUD de Músicas  
- [x] CRUD de Autores  
- [x] CRUD de Comentários  
- [ ] Implementação de autenticação (em desenvolvimento)

---

### 🧱 **Stack utilizada**

| Tipo | Tecnologias |
|------|--------------|
| **Linguagem** | Java 17 |
| **Framework** | Spring Boot |
| **Banco de Dados** | PostgreSQL |
| **ORM** | JPA / Hibernate |
| **Build Tool** | Maven |

---

### 🛣️ **Principais rotas**

Base URL: `http://localhost:8081/api`

| Route | Method | Description |
| --- | --- | --- |
| `/api/user` | GET | List all users |
| `/api/user/{id}` | GET | Find user by id |
| `/api/user` | POST | Register a new user |
| `/api/user` | PUT | Update an existent user |
| `/api/user` | DELETE | Remove an existent user |
| `/api/user/{id}` | DELETE | Remove an existent user by id |
| --- | --- | --- |
| `/api/playlist` | GET | List all playlists |
| `/api/playlist/{id}` | GET | Find playlist by id |
| `/api/playlist` | POST | Register a new playlist |
| `/api/playlist` | PUT | Update an existent playlist |
| `/api/playlist` | DELETE | Remove an existent playlist |
| `/api/playlist/{id}` | DELETE | Remove an existent playlist by id |
| --- | --- | --- |
| `/api/musica` | GET | List all musics |
| `/api/musica/{id}` | GET | Find music by id |
| `/api/musica` | POST | Register a new music |
| `/api/musica` | PUT | Update an existent music |
| `/api/musica` | DELETE | Remove an existent music |
| `/api/musica/{id}` | DELETE | Remove an existent music by id |
| --- | --- | --- |
| `/api/autor` | GET | List all authors |
| `/api/autor/{id}` | GET | Find author by id |
| `/api/autor` | POST | Register a new author |
| `/api/autor` | PUT | Update an existent author |
| `/api/autor` | DELETE | Remove an existent author |
| `/api/autor/{id}` | DELETE | Remove an existent author by id |
| --- | --- | --- |
| `/api/comentario` | GET | List all comments |
| `/api/comentario/{id}` | GET | Find comment by id |
| `/api/comentario` | POST | Register a new comment |
| `/api/comentario` | PUT | Update an existent comment |
| `/api/comentario` | DELETE | Remove an existent comment |
| `/api/comentario/{id}` | DELETE | Remove an existent comment by id |
---

### 🧪 **Como executar localmente**

```bash
# Clone o repositório
git clone https://github.com/Sena32/musicify-api.git

# Entre na pasta do projeto
cd musicify-api

# Execute o projeto
./mvnw spring-boot:run
```
<br />
<div align="center">
  <small>Developed by Ailton de Sena Pinheiro - 05/2023</small>

  [![GitHub Badge](https://img.shields.io/badge/Ailton_Sena-000?style=for-the-badge&logo=github&logoColor=white&link=https://www.linkedin.com/in/ailtonsenap)](https://github.com/Sena32/)
    [![Linkedin Badge](https://img.shields.io/badge/Ailton_Sena-000?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/ailtonsenap)](https://www.linkedin.com/in/ailtonsenap/) 
</div>
