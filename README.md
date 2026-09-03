#🌱 Xrural
##www.xrural.com.br
Marketplace digital para conectar o campo ao mercado.

A Xrural é uma plataforma de marketplace voltada para o agronegócio brasileiro, criada para conectar produtores rurais, compradores, fornecedores e prestadores de serviços em um único ambiente digital.

A plataforma permite anunciar, pesquisar e encontrar produtos e serviços relacionados ao meio rural, facilitando a conexão entre quem produz, vende, compra e presta serviços para o agronegócio.

🎯 Objetivo

A Xrural tem como objetivo digitalizar e simplificar a comercialização de produtos e serviços do setor rural, oferecendo um ambiente especializado para negócios relacionados ao agronegócio.

A plataforma busca aproximar o produtor do mercado e facilitar a descoberta de novas oportunidades no campo.

🚜 Principais categorias
🐄 Animais
🚜 Máquinas e implementos
🚗 Veículos
🌾 Imóveis rurais
🧪 Insumos
🥩 Nutrição animal
👨‍🌾 Serviços rurais
⚙️ Funcionalidades
👤 Usuários
Cadastro de usuários
Login e autenticação
Gerenciamento de perfil
Gerenciamento dos próprios anúncios
📢 Anúncios
Criação de anúncios
Edição e exclusão de anúncios
Upload de imagens
Definição de categoria
Descrição do produto ou serviço
Preço
Localização
Informações de contato
Status do anúncio
🔎 Busca
Pesquisa por palavras-chave
Filtros por categoria
Filtros por localização
Filtros por preço
Ordenação dos resultados
💬 Contato

Os interessados podem entrar em contato diretamente com os anunciantes para obter informações adicionais e negociar produtos ou serviços.

🛠️ Stack tecnológica
Backend
PHP
API e regras de negócio
Autenticação e gerenciamento de usuários
Processamento de anúncios
Validação e tratamento de dados
Banco de dados
MySQL
Modelagem relacional
Persistência de usuários
Anúncios
Categorias
Localizações e demais informações da plataforma
Frontend
TypeScript
JavaScript
HTML5
CSS3
Interface responsiva
Ferramentas
Git
GitHub
Composer
npm
🏗️ Arquitetura

A aplicação utiliza uma separação entre frontend, backend e banco de dados:

                   ┌─────────────────────┐
                   │       Usuário       │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │      Frontend       │
                   │    TypeScript       │
                   └──────────┬──────────┘
                              │
                              │ HTTP / API
                              ▼
                   ┌─────────────────────┐
                   │       Backend       │
                   │         PHP         │
                   └──────────┬──────────┘
                              │
                              │ SQL
                              ▼
                   ┌─────────────────────┐
                   │       MySQL         │
                   │      Database       │
                   └─────────────────────┘

cp .env.example .env
``
