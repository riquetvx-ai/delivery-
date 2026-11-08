# Delivery do Bairro — arquivos todos na raiz

## GitHub pelo celular
Extraia este ZIP e envie TODOS os arquivos que estão dentro dele diretamente para a página principal do repositório GitHub. Não envie somente o ZIP.

## Render
Crie um Web Service conectado ao repositório:
- Root Directory: vazio
- Build Command: npm install
- Start Command: npm start
- Environment Variable: DATABASE_URL = Internal Database URL do PostgreSQL

## Banco
No PostgreSQL do Render, abra o PSQL e execute todo o conteúdo de `database.sql`.

## Importante
Este é um MVP inicial. Os restaurantes e produtos são dados fictícios. Pix é apenas uma opção para combinar com o restaurante; não existe integração de cobrança real. Antes de vender, implemente autenticação, permissões, painel de restaurantes/entregadores, segurança, LGPD e testes. Não compartilhe DATABASE_URL.
