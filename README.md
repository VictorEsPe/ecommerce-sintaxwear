# 🛍️ SintaxWear E-commerce

Um projeto de e-commerce moderno e responsivo para venda de tênis e sneakers online, desenvolvido com HTML5, CSS3 e design responsivo.

---

## 📋 Tabela de Conteúdos

- [Sobre o Projeto](#sobre-o-projeto)
- [Características](#características)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Componentes](#componentes)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Estilos e Variáveis CSS](#estilos-e-variáveis-css)
- [Responsividade](#responsividade)
- [Futuras Melhorias](#futuras-melhorias)
- [Contribuições](#contribuições)

---

## 🎯 Sobre o Projeto

**SintaxWear** é um e-commerce especializado em tênis e sneakers, desenvolvido como parte dos exercícios DevQuest. O projeto apresenta uma interface moderna e profissional com foco em experiência do usuário, design responsivo e otimização para dispositivos móveis e desktop.

**Descrição em Meta Tag:** Compre tênis e sneakers online na SintaxWear. Encontre os melhores modelos para todas as ocasiões com preços incríveis.

---

## ✨ Características

- ✅ **Header Fixo e Responsivo**: Menu de navegação flutuante com suporte a mobile
- ✅ **Menu Mobile**: Toggle menu com ícone hambúrguer para dispositivos menores
- ✅ **Seção Hero**: Banner principal com destaque de produto (Krypton One)
- ✅ **Categorias de Produtos**: Casual, Esporte, Moderno e Futurista
- ✅ **Grid de Produtos**: Layout dinâmico com destaque de produtos
- ✅ **Newsletter**: Formulário de inscrição por e-mail
- ✅ **Redes Sociais**: Links para Instagram, WhatsApp, TikTok e Facebook
- ✅ **Navegação por Seções**: Categorias masculino, feminino e outlet
- ✅ **Acessibilidade**: Estrutura semântica HTML e atributos ARIA
- ✅ **Design Responsivo**: Adaptado para todos os tamanhos de tela

---

## 🏗️ Estrutura do Projeto

```
ecommerce-sintaxwear/
│
├── index.html                 # Página principal do e-commerce
├── README.md                  # Este arquivo
│
├── css/                       # Estilos CSS
│   ├── reset.css             # Reset de estilos padrão
│   ├── variables.css         # Variáveis CSS e tipografia
│   ├── base.css              # Estilos base e componentes gerais
│   │
│   └── components/           # Estilos dos componentes
│       ├── header.css        # Estilo do cabeçalho
│       ├── hero.css          # Estilo da seção hero
│       ├── product-category.css  # Estilo das categorias
│       ├── product-grid.css  # Estilo da grid de produtos
│       └── footer.css        # Estilo do rodapé
│
├── images/                   # Arquivos de mídia
│   ├── banners/             # Imagens de banners
│   │   ├── Hero.jpg         # Banner principal desktop
│   │   └── hero-mobile.jpg  # Banner principal mobile
│   │
│   ├── favicons/            # Ícones de favicon
│   ├── icons/               # Ícones do projeto
│   │   ├── menu-hamburguer.svg
│   │   ├── item-menu.svg
│   │   ├── help.svg
│   │   ├── bag-icon.svg
│   │   ├── instagram.svg
│   │   ├── whatsapp.svg
│   │   ├── tiktok.svg
│   │   └── facebook.svg
│   │
│   ├── logo/                # Logo da marca
│   │   └── Logo.svg
│   │
│   └── products/            # Imagens dos produtos
│
└── .git/                     # Controle de versão

```

---

## 🚀 Instalação

Não há dependências externas para instalar. O projeto funciona com HTML, CSS puro.

### Passos:

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/ecommerce-sintaxwear.git
```

2. **Navegue para a pasta do projeto:**

```bash
cd ecommerce-sintaxwear
```

3. **Abra no navegador:**
   - Abra o arquivo `index.html` diretamente no seu navegador, ou
   - Use um servidor local (recomendado):

     ```bash
     # Com Python 3
     python -m http.server 8000

     # Com Node.js (com http-server instalado)
     http-server

     # Com Live Server no VS Code
     Clique com direito em index.html > Open with Live Server
     ```

4. **Acesse no navegador:**

```
http://localhost:8000
```

---

## 💻 Como Usar

### Estrutura HTML Principal

A página é dividida em 4 seções principais:

1. **Header**: Navegação fixa com logo e menus
2. **Main**: Conteúdo principal com hero, categorias e produtos
3. **Footer**: Informações adicionais, newsletter e redes sociais

### Componentes Interativos

- **Menu Mobile**: Use o checkbox com classe `.menu-toggle` para abrir/fechar
- **Botões de Call-to-Action**: Classes `.btn-outline` e `.btn-filled`
- **Formulário de Newsletter**: Input de e-mail com validação HTML5

### Navegação

```
Header:
├── Logo (Página Inicial)
├── Categorias: Masculino, Feminino, Outlet
└── Atalhos: Nossas Lojas, Sobre, Conta, Ajuda, Carrinho

Hero Section:
└── Krypton One (Produto em Destaque)

Categories Section:
├── Casual
├── Esporte
├── Moderno
└── Futurista

Grid Section:
└── 6 Cards de Produtos em Destaque

Footer:
├── Newsletter
├── Redes Sociais
├── Navegação por Categoria
└── Informações Legais
```

---

## 🎨 Componentes

### 1. **Header**

- Navegação fixa (floating)
- Menu responsivo para mobile
- Logo clicável
- Ícones de conta, ajuda e carrinho

### 2. **Hero Section**

- Banner com imagem de fundo
- Overlay com conteúdo
- Título, subtítulo e call-to-action
- Dois botões: "Ver modelos" e "Comprar"

### 3. **Product Categories**

- 4 cards de categorias
- Efeito de overlay ao passar
- Links para filtros por categoria

### 4. **Product Grid**

- 6 cards de produtos
- Layout responsivo (grid)
- Card de destaque (Krypton One)
- Botões de CTA

### 5. **Footer**

- Newsletter com input de e-mail
- Links para redes sociais (4 plataformas)
- Navegação de rodapé por categoria
- Copyright

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição                             |
| ---------- | ------------------------------------- |
| **HTML5**  | Estrutura semântica                   |
| **CSS3**   | Estilos, Flexbox, Grid, Media Queries |
| **SVG**    | Ícones vetoriais                      |
| **Fonts**  | Google Fonts (Ubuntu)                 |
| **Git**    | Controle de versão                    |

### Recursos CSS Utilizados:

- ✅ Variáveis CSS (`:root`)
- ✅ Flexbox para layouts
- ✅ CSS Grid para grade de produtos
- ✅ Media Queries para responsividade
- ✅ Transições e animações
- ✅ Pseudo-classes (`:hover`, `:focus`)

---

## 📁 Estrutura de Pastas Detalhada

### `/css`

Contém todos os estilos organizados de forma modular:

- **reset.css**: Normaliza estilos padrão do navegador
- **variables.css**: Define variáveis CSS e tipografia
- **base.css**: Estilos globais, componentes `.btn`, etc.

### `/css/components`

Estilos separados por componente para melhor manutenção:

- **header.css**: Navegação e menu
- **hero.css**: Seção hero/banner
- **product-category.css**: Cards de categorias
- **product-grid.css**: Grid de produtos
- **footer.css**: Rodapé e newsletter

### `/images`

Organiza mídia por tipo:

- **banners/**: Imagens hero para diferentes resoluções
- **icons/**: Ícones SVG do projeto
- **logo/**: Logo da marca
- **products/**: Fotos dos produtos (a adicionar)

---

## 🎨 Estilos e Variáveis CSS

### Fonte Principal

```css
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap");

--fonte-principal: "Ubuntu", sans-serif;
```

### Classes de Botão

**Botão Outline:**

```css
.btn-outline {
  background-color: transparent;
  border: 2px solid #fff;
}
```

**Botão Preenchido:**

```css
.btn-filled {
  background-color: /* cor primária */;
  border: 2px solid /* cor primária */;
}
```

---

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints estratégicos:

```css
/* Desktop */
@media (min-width: 1280px) {
    /* Layout desktop otimizado */
}

/* Tablet */
@media (max-width: 1280px) and (min-width: 768px) {
    /* Ajustes para tablet */
}

/* Mobile */
@media (max-width: 768px) {
    /* Menu mobile
    /* Grid adaptado
    /* Fonte menor
}
```

### Características Responsivas:

- ✅ Header adaptado para mobile com menu toggle
- ✅ Grid de produtos reflow automático
- ✅ Menu hambúrguer em dispositivos pequenos
- ✅ Imagens de banner otimizadas por dispositivo
- ✅ Padding e margens ajustadas

---

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está disponível para fins educacionais como parte dos exercícios DevQuest.

---

## 👨‍💻 Autor

Desenvolvido por **Victor** como exercício de aprendizagem em DevQuest.

---

## 📞 Suporte

Para dúvidas ou sugestões sobre o projeto, entre em contato ou abra uma issue no repositório.

---

**Última atualização:** Janeiro de 2026
