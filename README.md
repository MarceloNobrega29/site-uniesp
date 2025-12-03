# 🎓 Site UNIESP

Projeto desenvolvido para a disciplina de **Frontend Avançado** do curso de **Sistemas para Internet** do UNIESP Centro Universitário, lecionada pelo professor **Kelson Almeida**.

## 📋 Sobre o Projeto

Site institucional da Faculdade UNIESP desenvolvido com React e React Bootstrap, apresentando informações sobre a instituição, notícias e políticas de proteção de dados.

## 🚀 Tecnologias Utilizadas

- **React** - Biblioteca JavaScript para construção de interfaces
- **React Router DOM** - Gerenciamento de rotas
- **React Bootstrap** - Componentes de interface responsivos
- **Vite** - Build tool e servidor de desenvolvimento
- **JavaScript (ES6+)** - Linguagem de programação

## 📁 Estrutura do Projeto

```
site-uniesp/
├── public/              # Arquivos públicos e imagens
│   ├── noticias/       # Imagens das notícias
│   └── uniesp.jpg      # Logo da instituição
├── src/
│   ├── components/     # Componentes reutilizáveis
│   │   ├── CustomNavbar.jsx    # Barra de navegação
│   │   ├── CustomFooter.jsx    # Rodapé
│   │   └── BanerAd.jsx         # Banner publicitário
│   ├── pages/          # Páginas da aplicação
│   │   ├── Inicial.jsx         # Página inicial
│   │   ├── Faculdade.jsx       # Sobre a faculdade
│   │   ├── Dpo.jsx             # DPO & LGPD
│   │   ├── Noticias.jsx        # Listagem de notícias
│   │   └── VisualizaNoticia.jsx # Detalhes da notícia
│   ├── App.jsx         # Componente principal
│   └── main.jsx        # Ponto de entrada
└── package.json        # Dependências do projeto
```

## 🎨 Funcionalidades

- ✅ Navegação responsiva com menu hambúrguer em dispositivos móveis
- ✅ Página inicial com informações institucionais
- ✅ Sistema de notícias com listagem e visualização individual
- ✅ Galeria de fotos nas notícias
- ✅ Rodapé com informações de contato e links úteis
- ✅ Design responsivo para todos os dispositivos
- ✅ Integração com React Router para navegação SPA

## 🔧 Como Executar o Projeto

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/MarceloNobrega29/site-uniesp.git
```

2. Entre na pasta do projeto:
```bash
cd site-uniesp
```

3. Instale as dependências:
```bash
npm install
```

4. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
```

5. Acesse no navegador:
```
http://localhost:5173
```

## 📦 Build para Produção

Para gerar a versão de produção:

```bash
npm run build
```

Os arquivos otimizados serão gerados na pasta `dist/`.

## 🎓 Informações Acadêmicas

- **Instituição:** UNIESP Centro Universitário
- **Curso:** Sistemas para Internet
- **Disciplina:** Frontend Avançado
- **Professor:** Kelson Almeida
- **Desenvolvedor:** Marcelo Nóbrega


---

Desenvolvido por [Marcelo Nóbrega](https://github.com/MarceloNobrega29)