# Projeto Laravel - Sistema de Postagens

Aplicação desenvolvida em Laravel e PHP que permite gerenciar postagens com funcionalidades como criação, edição, exclusão, comentários, curtidas e organização por categorias e tags.

## Índice
- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Requisitos para Execução](#requisitos-para-execução)
- [Instalação e Configuração](#instalação-e-configuração)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Introdução

O sistema permite criar, editar, excluir, comentar, curtir e descurtir postagens. Além disso, é possível organizar as postagens por categorias e tags, proporcionando uma experiência completa para gerenciamento de conteúdos.

## Funcionalidades

- **Gerenciamento de Postagens:**
  - Criar novas postagens.
  - Editar postagens existentes.
  - Excluir postagens.

- **Interações:**
  - Adicionar comentários às postagens.
  - Curtir e descurtir postagens.

- **Organização:**
  - Vincular categorias às postagens.
  - Adicionar tags às postagens.

## Tecnologias Utilizadas

- **Linguagem:** PHP
- **Framework:** Laravel
- **Banco de Dados:** MySQL
- **Frontend:** Blade Templates (HTML, CSS, Bootstrap, JavaScript)
- **Outras Ferramentas:** Composer, Artisan

## Requisitos para Execução

- **Servidor Local:** Ambiente como [XAMPP](https://www.apachefriends.org/index.html) ou [Laragon](https://laragon.org/).
- **PHP:** Versão 8.0 ou superior.
- **Composer:** Gerenciador de dependências do PHP.
- **Banco de Dados:** MySQL ou equivalente.

## Instalação e Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/lucasmarqoliv/Projeto-BLOG.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd projeto-BLOG
   ```

3. Instale as dependências do projeto:
   ```bash
   composer install
   ```

4. Configure o arquivo `.env`:
   - Copie o arquivo de exemplo:
     ```bash
     cp .env.example .env
     ```
   - Atualize as informações do banco de dados no arquivo `.env`.

5. Gere a chave da aplicação:
   ```bash
   php artisan key:generate
   ```

6. Execute as migrações para criar as tabelas no banco de dados:
   ```bash
   php artisan migrate
   ```

7. Opcional: Popule o banco de dados com dados iniciais:
   ```bash
   php artisan db:seed
   ```

8. Inicie o servidor local:
   ```bash
   php artisan serve
   ```

## Uso

Após configurar o projeto, acesse a aplicação em [http://localhost:8000](http://localhost:8000). Utilize as funcionalidades para criar, editar, e gerenciar postagens com categorias, tags e interações de curtidas e comentários.

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b minha-contribuicao
   ```
3. Faça suas alterações e commite-as:
   ```bash
   git commit -m 'Descrição da sua mudança'
   ```
4. Faça o push para a branch:
   ```bash
   git push origin minha-contribuicao
   ```
5. Abra um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

- **Email:** lucasmarqoliv@gmail.com
- **GitHub:** [lucasmarqoliv](https://github.com/lucasmarqoliv)

