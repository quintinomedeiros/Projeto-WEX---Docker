<p align="center">
<a href="https://dio.me/">
    <img 
        src="https://img.shields.io/badge/DIO-Code_The_Future-28DA77?logo=youtube" 
        alt="DIO - Code The Future">
</a>
<a href="https://dio.me/">
<img 
    src="https://img.shields.io/badge/🔴_LIVE_CODE-FF5E72" 
    alt="🔴 LIVE CODE">
</a>
</p>

# 🚀 Projeto Apache com Docker Compose

Este projeto demonstra como configurar e executar um servidor **Apache HTTP (httpd)** utilizando **Docker Compose**. Ele serve uma página web simples escrita em HTML e descreve todo o processo de forma educativa.

---

## 📦 Estrutura do Projeto

meu-apache-projeto/
├── docker-compose.yml
└── site/
└── index.html


---

## 🔧 Arquivo `docker-compose.yml`

O arquivo `docker-compose.yml` define os serviços e usa a imagem oficial do Apache (httpd), expondo a porta 8080 e montando a pasta `site` como volume:

```yaml
version: '3.8'

services:
  web:
    image: httpd:2.4
    ports:
      - "8080:80"
    volumes:
      - ./site:/usr/local/apache2/htdocs/
🧪 Como Executar o Projeto
No terminal, dentro da pasta do projeto:

bash
Copiar
Editar
docker compose up
Depois, acesse no navegador:

```bash
http://localhost:8080
```

Você verá a página HTML sendo servida pelo Apache, rodando dentro de um container Docker.

## 🌐 Subindo para o GitHub
Após criar um repositório no GitHub, execute os seguintes comandos no terminal:

```bash
git init
git remote add origin https://github.com/seu-usuario/meu-apache-docker.git
git add .
git commit -m "Subindo projeto Apache com Docker"
git branch -M main
git push -u origin main
```

Troque seu-usuario pelo seu nome de usuário do GitHub.

## ✅ Objetivos Atendidos
- Criar um arquivo docker-compose.yml com Apache (httpd)
- Definir volume com HTML simples ("Hello World")
- Executar a aplicação com Docker Compose
- Subir os arquivos para um repositório no GitHub

## 💡 Observações
Este projeto é ideal para quem está iniciando com Docker e Docker Compose. Ele mostra, na prática, como:
- Usar imagens oficiais do Docker Hub
- Definir volumes com arquivos HTML
- Rodar aplicações web em containers
- Organizar a estrutura de um projeto Dockerizado

## ⚖️ Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.

---

## 👨‍💻 Expert

<p align="left">
  <strong>Quintino Medeiros</strong><br>
  Desenvolvedor, educador e entusiasta de tecnologias Microsoft, com foco em formação técnica de alta qualidade. Este material é fruto de experiência prática e didática, pensado para ser uma fonte de referência clara e confiável.<br><br>
  <a href="https://github.com/quintinomedeiros">
    <img src="https://img.shields.io/badge/GitHub-quintinomedeiros-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/quintinomedeiros">
    <img src="https://img.shields.io/badge/LinkedIn-quintinomedeiros-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

---

> ⚙️ Este repositório é parte do projeto educacional mantido por Quintino Medeiros e é constantemente atualizado com novos conteúdos e práticas.
