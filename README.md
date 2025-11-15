🐟 Pesk — O maior site de pesca do Brasil

Pesk é uma plataforma web completa para apaixonados por pesca.
O projeto conta com frontend moderno em HTML/CSS/Bootstrap, integração com backend Node.js/Express, autenticação com JWT, logger, e armazenamento de dados em arquivos JSON.

🚀 Funcionalidades principais
🖥️ Front-end

Página inicial com carrossel de produtos e anúncios

Busca dinâmica por categorias (iscas, varas, molinetes, etc.)

Sessão de lançamentos e promoções

Integração com o PeskClub✦ (assinatura mensal)

Páginas de cadastro e login com feedback visual

Layout responsivo com Bootstrap 5 e fontes personalizadas

⚙️ Back-end

API desenvolvida em Node.js + Express


Logger para monitoramento de requisições e erros

Manipulação de dados usando arquivos JSON:

catalogo.json: produtos e categorias

usuarios.json: cadastro de usuários, senhas e dados de login

Rotas REST para login, cadastro, carrinho e PeskClub
<details>
  <summary><strong>📁 Pesk</strong></summary>
<br>

&nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 frontend/</summary>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 home.html
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 cadastro.html
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 peskclub.html
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 style.css
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <summary>📁 imagens/</summary>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 icones/</summary></details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Anuncios/</summary></details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Categorias/</summary></details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Produtos/</summary></details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; └── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <summary>📁 backend/</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 server.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 routes/</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 entrar.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 carrinho.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 club.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&F; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 middleware/</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 autenticacao.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 logger.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 token.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 data/</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 catalogo.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 users.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 package.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </details>
</details>



Após o login, o token é salvo no localStorage do navegador.

As rotas protegidas do backend exigem o token no header:

Authorization: Bearer <token>


O token é validado no middleware auth.js.

🧠 Tecnologias usadas

Front-end:

HTML5, CSS3, JavaScript

Bootstrap 5

Google Fonts (Nunito, Lovelo)

Back-end:

Node.js

Express


Middleware Logger

Manipulação de arquivos JSON

⚙️ Como rodar o projeto
1️⃣ Clonar o repositório
git clone https://github.com/seuusuario/pesk.git
cd pesk

2️⃣ Instalar dependências
cd backend
npm install

3️⃣ Rodar o servidor
node server.js


O servidor iniciará em:
👉 http://localhost:3000

4️⃣ Acessar o site

Abra frontend/home.html no navegador.
