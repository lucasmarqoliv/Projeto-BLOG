Projeto Laravel - Sistema de Postagens

Este repositório contém um projeto desenvolvido em Laravel e PHP para gerenciar postagens. O sistema permite criar, editar, excluir, comentar, curtir, descurtir postagens, além de vincular categorias e tags.

✨ Funcionalidades

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

🛠️ Tecnologias Utilizadas

Linguagem: PHP

Framework: Laravel

Banco de Dados: MySQL (ou equivalente configurado no projeto)

Frontend: Blade Templates (HTML, CSS, JavaScript)

Outras Ferramentas: Composer, Artisan

🔧 Requisitos para Execução

Servidor Local: Ambiente como XAMPP ou Laragon.

PHP: Versão 8.0 ou superior.

Composer: Gerenciador de dependências do PHP.

Banco de Dados: MySQL ou equivalente.

➕ Instalação e Configuração

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Acesse o diretório do projeto:

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

Acesse a aplicação em http://localhost:8000.

🌐 Estrutura do Projeto

Models: Representam as entidades do sistema (Postagem, Categoria, Tag, etc.).

Controllers: Contêm a lógica de negócio para gerenciar postagens, interações e organização.

Views: Interfaces do usuário construídas com Blade Templates.

Routes: Gerenciam as rotas da aplicação.

➖ Contribuição

Sinta-se à vontade para contribuir com melhorias para este projeto. Para contribuir:

Faça um fork deste repositório.

Crie uma branch para suas alterações:

git checkout -b minha-contribuicao

Envie suas alterações:

git push origin minha-contribuicao

Abra um pull request no GitHub.

📚 Licença

Este projeto está licenciado sob a MIT License.

📢 Contato

Para dúvidas ou sugestões, entre em contato:

Email: lucasmarqoliv@gmail.com

GitHub: lucasmarq
