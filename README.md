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
  <summary><strong>📁 Estrutura do Projeto</strong></summary>
<br>

📄 .gitignore
<br>
<details>
  <summary><strong>📁 Projeto-Pesk-main</strong></summary>
<br>

&nbsp;&nbsp;&nbsp; ├── 📄 .gitignore
&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; ├── 📄 Documentacao.docx
&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Projeto-Pesk</summary>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 .gitignore
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 README.md
&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; ├── 📄 README.md
&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; └── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <summary>📁 Servidor</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Back-end</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 data</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 catalogo.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 users.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 middlewares</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 autenticacao.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 logger.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 token.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <summary>📁 rotas</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 carrinho.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 catalogo.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 login.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Front-end</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 cadastro.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 carretilhas.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 carrinho.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 home.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 imagens</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Anuncios</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 anuncio-peskclub.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 anuncio1.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 anuncio2.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 anuncio3.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Categorias</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 categoria1.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 categoria2.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 categoria3.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 categoria4.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 categoria5.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 categoria6.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 icones</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 close-eye.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 icon-carrinho.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 icon-perfil.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 icon-redx.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 icon.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 logo.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 open-eye.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 peixe-fundo.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 PESK.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Produtos</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Carretilhas</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha11 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha32 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha33 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha34 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha35 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha36 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Carretilha37 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Carretilha38 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Iscas</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Anzol6 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Boia10 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Boia15 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Isca18 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Isca39 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Isca4 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Isca40 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Isca41 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Linhas</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha3 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha42 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha43 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha44 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha45 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha46 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Linha47 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Linha48 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Molinets</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete14 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete2 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete26 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete27 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete28 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete29 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Molinete30 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Molinete31 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 Outros</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Allicate8 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Balanca20 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Cadeira13 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Caixa12 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Caixa5 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Camisa19 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Chapeu7 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Lanterna22 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 Peskclub-49 (PESKclub.png)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <summary>📁 Varas</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Porta16 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Suporte9 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 SupVara17 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Vara23 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Vara24 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 Vara25 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details><summary>📁 varaShimanoFX6-6 (3 arquivos .png)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── <details><summary>📁 varaTelescopiaGomo3m21 (img1, img2, img3)</summary></details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── <details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <summary>📁 sobre</summary>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 10promo.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 Brasil-preto-club.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 Presente-preto-club.png
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 Thumbs.db
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 iscas.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 linhas.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 login.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 molinetes.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 naoautorizado.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 outros.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&Dnbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 peskclub.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 sobre.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 style.css
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 telaproduto.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 varas.html
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; </details>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 package-lock.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 package.json
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; ├── 📄 server.js
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; └── 📄 Thumbs.db
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </details>
<br>
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
