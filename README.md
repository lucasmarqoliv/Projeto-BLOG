Projeto Laravel - Sistema de Postagens

Aplicação desenvolvida em Laravel e PHP que permite gerenciar postagens com funcionalidades como criação, edição, exclusão, comentários, curtidas e organização por categorias e tags.

Índice

Introdução

Funcionalidades

Tecnologias Utilizadas

Requisitos para Execução

Instalação e Configuração

Uso

Contribuição

Licença

Contato

Introdução

O sistema permite criar, editar, excluir, comentar, curtir e descurtir postagens. Além disso, é possível organizar as postagens por categorias e tags, proporcionando uma experiência completa para gerenciamento de conteúdos.

Funcionalidades

Gerenciamento de Postagens:

Criar novas postagens.

Editar postagens existentes.

Excluir postagens.

Interações:

Adicionar comentários às postagens.

Curtir e descurtir postagens.

Organização:

Vincular categorias às postagens.

Adicionar tags às postagens.

Tecnologias Utilizadas

Linguagem: PHP

Framework: Laravel

Banco de Dados: MySQL (ou equivalente configurado no projeto)

Frontend: Blade Templates (HTML, CSS, JavaScript)

Outras Ferramentas: Composer, Artisan

Requisitos para Execução

Servidor Local: Ambiente como XAMPP ou Laragon.

PHP: Versão 8.0 ou superior.

Composer: Gerenciador de dependências do PHP.

Banco de Dados: MySQL ou equivalente.

Instalação e Configuração

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Navegue até o diretório do projeto:

cd seu-repositorio

Instale as dependências do projeto:

composer install

Configure o arquivo .env:

Copie o arquivo de exemplo:

cp .env.example .env

Atualize as informações do banco de dados no arquivo .env.

Gere a chave da aplicação:

php artisan key:generate

Execute as migrações para criar as tabelas no banco de dados:

php artisan migrate

Opcional: Popule o banco de dados com dados iniciais:

php artisan db:seed

Inicie o servidor local:

php artisan serve

Uso

Após configurar o projeto, acesse a aplicação em http://localhost:8000. Utilize as funcionalidades para criar, editar, e gerenciar postagens com categorias, tags e interações de curtidas e comentários.

Contribuição

Contribuições são bem-vindas! Para contribuir:

Faça um fork deste repositório.

Crie uma nova branch:

git checkout -b minha-contribuicao

Faça suas alterações e commite-as:

git commit -m 'Descrição da sua mudança'

Faça o push para a branch:

git push origin minha-contribuicao

Abra um pull request.

Licença

Este projeto está licenciado sob a MIT License.

Contato

Email: seuemail@exemplo.com

GitHub: seu-usuario
