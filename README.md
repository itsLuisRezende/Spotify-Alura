<img width="1883" height="799" alt="Captura de tela 2025-08-28 181557" src="https://github.com/user-attachments/assets/8cddf275-6133-40ef-b72a-32ed868be082" />

#  Projeto Spotify – Alura

## 1. Objetivo do projeto
Criar uma interface inspirada no estilo do Spotify, aplicando conceitos de consumo de APIs, layout responsivo e manipulação do DOM. O projeto foi desenvolvido durante um curso da Alura com o objetivo de consolidar habilidades em JavaScript, HTML e CSS, além de praticar requisições dinâmicas e interação com dados externos.

## 2. Resultado
Foi construída uma página que exibe músicas ou playlists consultadas via API (ou dados simulados), com funcionalidade de navegação visual e interatividade. O layout segue o padrão visual moderno de plataformas de streaming, e a aplicação responde dinamicamente às interações do usuário, proporcionando uma experiência fluida e esteticamente agradável.

## 3. Ferramentas utilizadas
- **HTML5** – estrutura semântica da página  
- **CSS3** – estilos visuais e responsividade (flexbox, grid, etc.)  
- **JavaScript (Vanilla JS)** – lógica e manipulação do DOM  
- **Fetch API / XMLHttpRequest** – requisição e consumo de dados da API  
- **VS Code** (ou outro editor de código) – ambiente de desenvolvimento  
- **Git & GitHub** – controle de versão e hospedagem do código  

## 4. O que eu aprendi (habilidades/competências adquiridas)
- Realizar requisições HTTP para APIs externas e tratar respostas de forma assincrônica (usando `fetch` ou `async/await`)
- Aplicar dinamicamente dados em elementos HTML via JavaScript
- Criar layouts responsivos e modernos com CSS, utilizando boas práticas de UI/UX
- Organizar código, modularizar funções e manter estrutura limpa e legível
- Versionar o projeto com Git e publicar no GitHub, documentando progresso

## 5. Melhorias a serem feitas:
- Integrar o código com a API oficial do Spotify, usando autenticação OAuth2, para buscar dados reais como playlists, álbuns e faixas.
- Adicionar filtros de busca, paginação ou carregamento infinito para melhorar a UX.
- Incluir efeitos visuais e transições CSS para tornar a interface mais atraente e interativa.
- Implementar testes (unitários e de integração) para garantir estabilidade das funcionalidades.
- Fazer deploy online (por exemplo, via GitHub Pages ou Netlify) para disponibilizar o projeto como demonstração pública.

## Passo a passo da execução

- Clone o repositório
- Abrir diretamente no navegador:
    Encontre o arquivo index.html na raiz do projeto
    Dê um duplo clique para abri-lo diretamente no navegador — a aplicação deve rodar normalmente, já que é uma SPA simples

- (Recomendado) Usar servidor local
Para evitar potenciais limitações de CORS ou bloqueios de requisições via fetch, é interessante servir os arquivos via um servidor local simples:

Python (se instalado):

# Python 3.x
python3 -m http.server 8000

Acesse http://localhost:8000 no navegador.

Node.js (se instalado):

npm install -g serve
serve

Ou, se quiser, pode usar um script como npx http-server:

npx http-server

