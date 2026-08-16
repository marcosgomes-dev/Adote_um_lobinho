# 🐺 Adote um Lobinho

Site desenvolvido como parte de um **processo seletivo para uma empresa júnior**, com o objetivo de simular uma plataforma de adoção de lobos. O projeto permite visualizar, cadastrar, adotar e excluir "lobinhos", com todos os dados persistidos no `localStorage` do navegador.

## 📋 Sobre o projeto

O **Adote um Lobinho** é uma aplicação web front-end onde o usuário pode:

- Conhecer a instituição fictícia e seus valores;
- Navegar por uma lista de lobos disponíveis para adoção;
- Pesquisar lobinhos por nome e filtrar apenas os já adotados;
- Visualizar detalhes de cada lobinho;
- Preencher um formulário para adotar um lobinho;
- Cadastrar novos lobinhos no sistema;
- Excluir lobinhos da lista.

## ✨ Funcionalidades

- **Home** — apresentação do projeto, seção "Sobre", valores da instituição e destaque de dois lobinhos exibidos aleatoriamente.
- **Nossos Lobinhos** — listagem com busca por nome, filtro de lobinhos adotados e paginação.
- **Detalhes do Lobinho** — página individual com opções de adotar ou excluir o lobinho.
- **Adotar Lobinho** — formulário para registrar os dados do adotante (nome, idade e e-mail).
- **Adicionar Lobinho** — formulário para cadastrar um novo lobinho (nome, idade, foto e descrição).
- **Quem Somos** — página institucional sobre a organização.

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **LocalStorage** para persistência dos dados no navegador
- **Google Fonts** (Darker Grotesque, Roboto, Alata)

## 📁 Estrutura do projeto

```
├── index.html                 # Página inicial
├── listaDeLobinhos.html       # Listagem de lobinhos
├── showLobinho.html           # Detalhes do lobinho
├── adotarLobinho.html         # Formulário de adoção
├── adicionar-lobinhos.html    # Formulário de cadastro
├── quemSomos.html             # Página institucional
├── style.css                  # Estilos da Home
├── listaDeLobinhos.css        # Estilos da listagem
├── showlobinho.css            # Estilos da página de detalhes
├── adotar-lobinhos.css        # Estilos do formulário de adoção
├── adicionar-lobinhos.css     # Estilos do formulário de cadastro
├── quemSomos.css              # Estilos da página institucional
├── script.js                  # Lógica da aplicação (CRUD, paginação, busca)
└── lobinhos.json              # Dados iniciais dos lobinhos
```

## 🚀 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/DesafioAdoteUmLobinho.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd DesafioAdoteUmLobinho
   ```
3. Abra o arquivo `index.html` no navegador (recomenda-se usar uma extensão como o **Live Server**, do VS Code, para evitar problemas de CORS ao carregar o `lobinhos.json`).

## 💾 Persistência dos dados

Na primeira execução, os dados do arquivo `lobinhos.json` são carregados e salvos no `localStorage` do navegador. A partir daí, todas as operações de adoção, cadastro e exclusão de lobinhos são feitas diretamente no `localStorage`.

> ⚠️ Como os dados ficam armazenados no navegador, limpar o cache/localStorage reinicia a lista de lobinhos para o estado original do `lobinhos.json`.

## 👤 Autor

Projeto desenvolvido por **[seu nome aqui]** como parte do processo seletivo de uma empresa júnior.
