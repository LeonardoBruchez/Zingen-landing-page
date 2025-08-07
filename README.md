# 🎵 Zingen - Landing Page

> **Projeto desenvolvido durante a trilha FullStack da Rocketseat** 🚀

Uma landing page responsiva para um aplicativo de karaokê fictício chamado "Zingen", desenvolvida com foco em **responsividade e media queries** para treinamento de habilidades front-end.

## 📋 Sobre o Projeto

Este projeto foi criado **exclusivamente para fins educacionais** durante o curso da Rocketseat, sem qualquer intenção comercial. O objetivo principal foi praticar e aprimorar habilidades de desenvolvimento front-end, especialmente:

- ✨ **Responsividade com Media Queries**
- 🎨 **Design System com CSS Custom Properties**
- 📱 **Layout Mobile-First**
- 🎯 **Componentização de CSS**

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna com:
  - **CSS Custom Properties (Variáveis CSS)** - Sistema de design consistente
  - **CSS Grid** - Layouts responsivos e flexíveis
  - **Flexbox** - Alinhamento e distribuição de elementos
  - **Media Queries** - Responsividade para diferentes tamanhos de tela
  - **CSS Container Queries** - Layouts adaptativos baseados no container

### **Design & UX**
- **Figma** - Design reproduzido fielmente do layout criado no Figma
- **Google Fonts (Inter)** - Tipografia profissional importada do Google Fonts
- **SVG Icons** - Ícones vetoriais escaláveis
- **Gradientes CSS** - Efeitos visuais modernos

## 🎨 Processo de Desenvolvimento

### **Design to Code** 🎯
- **Figma** - Layout completo criado e organizado no Figma
- **Reprodução fiel** - Código desenvolvido seguindo exatamente o design do Figma
- **Componentização** - Elementos do Figma transformados em componentes CSS reutilizáveis
- **Responsividade** - Adaptação do design mobile-first para diferentes breakpoints

## 📱 Tipos de Layout Implementados

### **1. Mobile-First Approach** 📱
- Layout otimizado para dispositivos móveis
- Breakpoint principal: `80em` (1280px)
- Classes utilitárias como `.desktop-only` para controle de visibilidade

### **2. Grid System** 🔲
- **`.even-columns`** - Colunas responsivas
- **`.grid`** - Layouts em grade
- **`.flex`** - Alinhamento flexível

### **3. Componentes Responsivos** 🧩
- **Header** - Navegação adaptativa
- **Hero Section** - CTA principal
- **Cards** - Componentes de conteúdo
- **Pricing Tables** - Planos e preços
- **Footer** - Links e redes sociais

## 🎨 Sistema de Design

### **Cores**
```css
--bg-color: #09090b          /* Fundo escuro */
--surface-color: #18181B     /* Superfícies */
--stroke-color: #27272A      /* Bordas */
--txt-color-primary: #F4F4F5 /* Texto principal */
--brand-color-primary: #F7B733 /* Laranja */
--brand-color-secondary: #FC4A1A /* Vermelho */
```

### **Tipografia**
- **Fonte**: Inter (Google Fonts) - Importada via CDN do Google Fonts
- **Pesos**: 400, 500, 800
- **Tamanhos**: Sistema escalável com variáveis CSS
- **Carregamento**: Otimizado com preconnect para melhor performance

### **Espaçamento**
- Sistema de padding consistente
- Classes utilitárias: `.py-base`, `.py-lg`, `.py-xl`

## 📁 Estrutura do Projeto

```
Zingen-landing-page/
├── 📄 index.html              # Página principal
├── 📁 styles/                 # Arquivos CSS
│   ├── 📄 index.css          # Arquivo principal (imports)
│   ├── 📄 global.css         # Reset e variáveis globais
│   ├── 📄 utility.css        # Classes utilitárias
│   ├── 📄 buttons.css        # Estilos de botões
│   ├── 📄 header.css         # Header responsivo
│   ├── 📄 hero.css           # Seção hero
│   ├── 📄 cards.css          # Componentes de cards
│   ├── 📄 features.css       # Seção de funcionalidades
│   ├── 📄 pricing.css        # Tabelas de preços
│   ├── 📄 download.css       # Seção de download
│   ├── 📄 footer.css         # Footer
│   └── 📄 social.css         # Ícones sociais
└── 📁 assets/                # Recursos visuais
    ├── 📁 icons/             # Ícones SVG
    ├── 📄 logo.svg           # Logo da marca
    ├── 📄 *.png              # Imagens de telas
    └── 📄 *.svg              # Ilustrações
```

## 🚀 Como Executar

1. **Clone o repositório**
   ```bash
   git clone [url-do-repositorio]
   cd Zingen-landing-page
   ```

2. **Abra o arquivo HTML**
   - Abra o arquivo `index.html` em qualquer navegador moderno
   - Ou use um servidor local para desenvolvimento

3. **Para desenvolvimento local**
   ```bash
   # Usando Python
   python -m http.server 8000
   
   # Usando Node.js
   npx serve .
   
   # Usando Live Server (VS Code)
   # Instale a extensão Live Server e clique em "Go Live"
   ```

## 📱 Responsividade

### **Breakpoints**
- **Mobile**: < 1280px (padrão)
- **Desktop**: ≥ 1280px (`80em`)

### **Classes Responsivas**
- `.desktop-only` - Elementos visíveis apenas no desktop
- `.container` - Container responsivo com largura máxima
- `.even-columns` - Grid que se adapta ao tamanho da tela

## 🎯 Funcionalidades Implementadas

### **Seções da Landing Page**
- ✅ **Header** - Navegação responsiva
- ✅ **Hero** - CTA principal com gradientes
- ✅ **About** - Apresentação do app
- ✅ **Features** - Cards de funcionalidades
- ✅ **Pricing** - Planos e preços
- ✅ **Download** - Links para app stores
- ✅ **Footer** - Links e redes sociais

### **Componentes**
- ✅ **Cards** - Componentes reutilizáveis
- ✅ **Buttons** - Botões com estados hover
- ✅ **Social Icons** - Ícones de redes sociais
- ✅ **Pricing Tables** - Tabelas de preços responsivas

## 🎨 Destaques do Design

### **Visual Moderno**
- 🎨 **Tema escuro** com cores vibrantes
- 🌈 **Gradientes** nos elementos interativos
- 📱 **Mobile-first** com transições suaves
- 🎯 **Call-to-actions** bem destacados

### **Acessibilidade**
- ♿ **Semântica HTML** adequada
- 🎨 **Contraste** de cores adequado
- 📱 **Navegação por teclado** funcional
- 🏷️ **Alt text** em imagens

## 📚 Aprendizados

Este projeto foi fundamental para praticar:

- 🎯 **Media Queries** e responsividade
- 🎨 **CSS Custom Properties** para design system
- 📱 **Mobile-first** development
- 🧩 **Componentização** de CSS
- 🎨 **Design responsivo** moderno
- 📐 **Layouts flexíveis** com Grid e Flexbox

## 📄 Licença

Este projeto foi desenvolvido **exclusivamente para fins educacionais** durante o curso da Rocketseat. Não possui fins comerciais.

---

**Desenvolvido com ❤️ durante a trilha FullStack da Rocketseat** 🚀 