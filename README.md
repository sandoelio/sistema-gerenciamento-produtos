# Gestão de Produtos com Laravel
## 📋 Sobre o Projeto
Este projeto é um sistema de gestão de produtos desenvolvido com o framework Laravel. Ele permite realizar o cadastro, edição, exclusão e listagem de produtos, com um design moderno utilizando o Blade (sistema de templates do Laravel). Foi configurado com Docker para facilitar o desenvolvimento em ambientes padronizados, e utiliza o Composer para gerenciamento de dependências.

---
## ✨ Funcionalidades

* Cadastro de novos produtos.
* Edição e atualização de informações de produtos existentes.
* Exclusão segura de produtos.
* Listagem organizada com design clean utilizando Blade.
* Sistema modular e escalável, com banco de dados relacional.

---
## 🛠️ Tecnologias Utilizadas

* Laravel: Framework PHP utilizado para o backend e estrutura MVC.
* Blade: Sistema de templates nativo do Laravel para renderizar as páginas.
* Docker: Padronização do ambiente de desenvolvimento.
* Composer: Gerenciador de dependências para PHP.
* HTML/CSS: Estruturação e estilização da interface.

---
## 📂 Estrutura do Projeto
```
sistema-gerenciamento-produtos/
├── app/                 # Diretório principal do Laravel
├── bootstrap/           # Configuração inicial do framework
├── config/              # Arquivos de configuração do Laravel
├── database/            # Migrations e seeders para o banco de dados
├── public/              # Arquivos públicos (CSS, JS, imagens)
├── resources/
│   ├── views/           # Templates Blade do projeto
│   │   └── products/    # Páginas relacionadas à gestão de produtos
├── routes/
│   └── web.php          # Rotas principais da aplicação
├── docker-compose.yml   # Configuração do Docker para o ambiente
├── .env                 # Arquivo de configuração de ambiente
├── composer.json        # Dependências do projeto PHP
└── README.md            # Documentação do projeto

```
----
## 🚀 Como Executar o Projeto

1. Clone o repositório:
```
git clone https://github.com/sandoelio/gestao-produtos-laravel.git

```
2. Suba o ambiente com Docker caso decida usar o ambiente:
 * Certifique-se de ter o Docker instalado em sua máquina.
 * Na pasta raiz do projeto, execute:
  ```
    docker-compose up -d
  ```
3. Instale as dependências com Composer:
   ```
   composer install   
   ```
4. Configure o arquivo .env: 
    * Atualize as configurações de banco de dados no arquivo .env, caso necessário
      
5. Instale a key do laravel
 ```
   php artisan key:generate
 ```
*  Rode as migrates
* Rode as seeds

6. Acesse a aplicação no navegador:
    * URL padrão: http://localhost
---
# 📧 Contato
Se precisar de mais informações, entre em contato:

* Autor: Sandoelio Silva
* Email: sandoelio@hotmail.com
* LinkedIn: [Sandoelio Silva](https://www.linkedin.com/in/sandoelio-silva/)
