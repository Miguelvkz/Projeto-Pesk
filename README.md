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
<summary>📁 Estrutura do Projeto (Clique para expandir o código)</summary>
- .gitignore
- Projeto-Pesk-main
  - .gitignore
  - Documentacao.docx
  - Projeto-Pesk
    - .gitignore
    - README.md
  - README.md
  - Servidor
    - Back-end
      - data
        - catalogo.json
        - users.json
      - middlewares
        - autenticacao.js
        - logger.js
        - token.js
      - rotas
        - carrinho.js
        - catalogo.js
        - login.js
    - Front-end
      - cadastro.html
      - carretilhas.html
      - carrinho.html
      - home.html
      - imagens
        - Anuncios
          - anuncio-peskclub.png
          - anuncio1.png
          - anuncio2.png
          - anuncio3.png
        - Categorias
          - categoria1.png
          - categoria2.png
          - categoria3.png
          - categoria4.png
          - categoria5.png
          - categoria6.png
        - icones
          - close-eye.png
          - icon-carrinho.png
          - icon-perfil.png
          - icon-redx.png
          - icon.png
          - logo.png
          - open-eye.png
          - peixe-fundo.png
          - PESK.png
        - Produtos
          - Carretilhas
            - Carretilha11
              - img1.png
              - img2.png
              - img3.png
            - Carretilha32
              - img1.png
              - img2.png
              - img3.png
            - Carretilha33
              - img1.png
              - img2.png
              - img3.png
            - Carretilha34
              - img1.png
              - img2.png
              - img3.png
            - Carretilha35
              - img1.png
              - img2.png
              - img3.png
            - Carretilha36
              - img1.png
              - img2.png
              - img3.png
            - Carretilha37
              - img1.png
              - img2.png
              - img3.png
            - Carretilha38
              - img1.png
              - img2.png
              - img3.png
          - Iscas
            - Anzol6
              - img1.png
              - img2.png
              - img3.png
            - Boia10
              - img1.png
              - img2.png
              - img3.png
            - Boia15
              - img1.png
              - img2.png
              - img3.png
            - Isca18
              - img1.png
              - img2.png
              - img3.png
            - Isca39
              - img1.png
              - img2.png
              - img3.png
            - Isca4
              - img1.png
              - img2.png
              - img3.png
            - Isca40
              - img1.png
              - img2.png
              - img3.png
            - Isca41
              - img1.png
              - img2.png
              - img3.png
          - Linhas
            - Linha3
              - img1.png
              - img2.png
              - img3.png
            - Linha42
              - img1.png
              - img2.png
              - img3.png
            - Linha43
              - img1.png
              - img2.png
              - img3.png
            - Linha44
              - img1.png
              - img2.png
              - img3.png
            - Linha45
              - img1.png
              - img2.png
              - img3.png
            - Linha46
              - img1.png
              - img2.png
              - img3.png
            - Linha47
              - img1.png
              - img2.png
              - img3.png
            - Linha48
              - img1.png
              - img2.png
              - img3.png
          - Molinets
            - Molinete14
              - img1.png
              - img2.png
              - img3.png
            - Molinete2
              - img1.png
              - img2.png
              - img3.png
            - Molinete26
              - img1.png
              - img2.png
              - img3.png
            - Molinete27
              - img1.png
              - img2.png
              - img3.png
            - Molinete28
              - img1.png
              - img2.png
              - img3.png
            - Molinete29
              - img1.png
              - img2.png
              - img3.png
            - Molinete30
              - img1.png
              - img2.png
              - img3.png
            - Molinete31
              - img1.png
              - img2.png
              - img3.png
          - Outros
            - Allicate8
              - img1.png
              - img2.png
              - img3.png
            - Balanca20
              - img1.png
              - img2.png
              - img3.png
            - Cadeira13
              - img1.png
              - img2.png
              - img3.png
            - Caixa12
              - img1.png
              - img2.png
              - img3.png
            - Caixa5
              - img1.png
              - img2.png
              - img3.png
            - Camisa19
              - img1.png
              - img2.png
              - img3.png
            - Chapeu7
              - img1.png
              - img2.png
              - img3.png
            - Lanterna22
              - img1.png
              - img2.png
              - img3.png
            - Peskclub-49
              - PESKclub.png
          - Varas
            - Porta16
              - img1.png
              - img2.png
              - img3.png
            - Suporte9
              - img1.png
              - img2.png
              - img3.png
            - SupVara17
              - img1.png
              - img2.png
              - img3.png
            - Vara23
              - img1.png
              - img2.png
              - img3.png
            - Vara24
              - img1.png
              - img2.png
              - img3.png
            - Vara25
              - img1.png
              - img2.png
              - img3.png
            - varaShimanoFX6-6
              - VaraShimano66-1.png
              - VaraShimano66-2.png
              - VaraShimano66.png
            - varaTelescopiaGomo3m21
              - img1.png
              - img2.png
              - img3.png
        - sobre
          - 10promo.png
          - Brasil-preto-club.png
          - Presente-preto-club.png
        - Thumbs.db
      - iscas.html
      - linhas.html
      - login.html
      - molinetes.html
      - naoautorizado.html
      - outros.html
      - peskclub.html
      - sobre.html
      - style.css
      - telaproduto.html
      - varas.html
    - package-lock.json
    - package.json
    - server.js
    - Thumbs.db
- README.md
- Servidor
  - Back-end
    - data
      - catalogo.json
      - users.json
    - middlewares
      - autenticacao.js
      - logger.js
    - rotas
      - catalogo.js
      - login.js
  - Front-end
    - cadastro.html
    - carrinho.html
    - home.html
    - imagens
      - Anuncios
        - anuncio-peskclub.png
        - anuncio1.png
        - anuncio2.png
        - anuncio3.png
      - Categorias
        - categoria1.png
        - categoria2.png
        - categoria3.png
        - categoria4.png
        - categoria5.png
        - categoria6.png
      - icones
        - close-eye.png
        - icon-carrinho.png
        - icon-perfil.png
        - icon-redx.png
        - icon.png
        - logo.png
        - open-eye.png
      - Produtos
        - Carretilhas
          - Carretilha11
            - img1.png
            - img2.png
            - img3.png
        - Iscas
          - Anzol6
            - img1.png
            - img2.png
            - img3.png
          - Boia10
            - img1.png
            - img2.png
            - img3.png
          - Boia15
            - img1.png
            - img2.png
            - img3.png
          - Isca18
            - img1.png
            - img2.png
            - img3.png
          - Isca4
            - img1.png
            - img2.png
            - img3.png
        - Linhas
          - Linha3
            - img1.png
            - img2.png
            - img3.png
        - Molinets
          - Molinete14
            - img1.png
            - img2.png
            - img3.png
          - molinetearena4000
            - img1.png
            - img2.png
            - img3.png
        - Outros
          - Allicate8
            - img1.png
            - img2.png
            - img3.png
          - Balanca20
            - img1.png
            - img2.png
            - img3.png
          - Cadeira13
            - img1.png
            - img2.png
            - img3.png
          - Caixa12
            - img1.png
            - img2.png
            - img3.png
          - Caixa5
            - img1.png
            - img2.png
            - img3.png
          - Camisa19
            - img1.png
            - img2.png
            - img3.png
          - Chapeu7
            - img1.png
            - img2.png
            - img3.png
          - Lanterna22
            - img1.png
            - img2.png
            - img3.png
        - Varas
          - Porta16
            - img1.png
            - img2.png
            - img3.png
          - Suporte9
            - img1.png
            - img2.png
            - img3.png
          - SupVara17
            - img1.png
            - img2.png
            - img3.png
          - varaShimanoFX6-6
            - VaraShimano66-1.png
            - VaraShimano66-2.png
            - VaraShimano66.png
          - varaTelescopiaGomo3m
            - img1.png
            - img2.png
            - img3.png
      - sobre
        - 10promo.png
        - Brasil-preto-club.png
        - Presente-preto-club.png
      - Thumbs.db
    - login.html
    - naoautorizado.html
    - peskclub.html
    - style.css
    - telapagamento.html
    - telaproduto.html
  - package-lock.json
  - package.json
  - server.js
  - Thumbs.db

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
