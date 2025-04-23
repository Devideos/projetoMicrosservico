# 🚀 Projeto: Microsserviços com Docker e Nginx

## 📌 Descrição
Este projeto foi desenvolvido como parte de um desafio proposto na plataforma Digital Innovation One, com o objetivo de aplicar conceitos de **containers** e **arquitetura de microsserviços** usando **Docker**, **PHP**, **MySQL** e **Nginx**. O cenário simula um ambiente escalável onde diversos serviços podem ser isolados e gerenciados de forma independente.

## 🧠 Pré-requisitos
Antes de executar o projeto, certifique-se de ter instalado:
- Docker
- Docker Compose
- Git
- Conhecimentos básicos em Linux, Docker e AWS

## 🧱 Arquitetura
A aplicação está estruturada da seguinte forma:

- `index.php`: Arquivo principal da aplicação PHP.
- `nginx.conf`: Configuração do Nginx como load balancer para múltiplas instâncias PHP.
- `banco.sql`: Script de inicialização do banco de dados MySQL.
- `Dockerfile`: Define a imagem do serviço PHP.
- `docker-compose.yml`: Orquestra os serviços (a ser incluído).

```
📦 projeto-microsservicos
├── banco.sql
├── dockerfile
├── index.php
├── nginx.conf
└── README.md
```

## 🛠️ Tecnologias Utilizadas
- PHP
- Nginx
- MySQL
- Docker / Docker Compose
- AWS (opcional para deploy)

## ▶️ Como Executar Localmente
**(docker-compose ainda será criado)**

1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/projeto-microsservicos.git
cd projeto-microsservicos
```

2. Construa e suba os containers:
```bash
docker-compose up --build
```

3. Acesse a aplicação no navegador:
```
http://localhost:4500
```

## 📈 Melhorias Futuras
- Criar um `docker-compose.yml` para orquestração completa
- Implementar CI/CD com GitHub Actions
- Deploy automatizado em ambiente AWS
- Logs centralizados com ELK ou Grafana + Loki

## 📸 Prints ou GIFs
*(Adicione imagens ou vídeos aqui mostrando a aplicação em execução)*

## 🧑‍💻 Autor
Desenvolvido por **David Pereira**.

---
**Inspire-se na história de Toshiro Shibakita e siga evoluindo na nuvem ☁️🚀**
