Aqui está o README da API de Receitas no mesmo estilo:

🍳 API de Receitas Culinárias
API RESTful para gerenciamento de receitas culinárias, chefs, usuários e interações sociais como curtidas, favoritos e comentários.

🚀 Tecnologias Utilizadas

Backend: Node.js
Banco de Dados: MySQL
ORM: Sequelize
Autenticação: JWT
Upload de Arquivos: Multer
Documentação: Swagger/OpenAPI


📌 Funcionalidades
👨‍🍳 Chefs

CRUD completo com paginação e busca
Vínculo com receitas cadastradas

🍽️ Receitas

CRUD com filtros e paginação
Vínculo a chefs responsáveis
Upload de imagens via Multer

👤 Usuários

Registro e autenticação
Atualização de perfil
Segurança com hash de senha

🔐 Autenticação JWT

Login e logout
Refresh token
Middleware de proteção de rotas

❤️ Interações Sociais

Favoritas: Usuários podem salvar e gerenciar receitas favoritas
Curtidas: Curtir/descurtir receitas com ranking das mais populares
Comentários: CRUD com avaliação por estrelas e moderação


📄 Rotas Principais
Após iniciar o servidor, acesse a documentação completa das rotas via Swagger em:
http://localhost:3000/api-docs

⚙️ Instalação e Configuração
1. Clone o repositório
bashgit clone https://github.com/caioarchive/api_receitas.git
cd api-receitas
2. Instale as dependências
bashnpm install
3. Execute o projeto
bashnpm run dev

🔐 Credenciais de Acesso
Para testar a API, utilize as seguintes credenciais:

Usuário: email@test.com · Senha: senha123


🚀 Objetivo
O projeto busca oferecer uma API completa para plataformas culinárias, garantindo:

Organização e escalabilidade
Autenticação segura
Interações sociais entre usuários
Documentação clara e acessível
