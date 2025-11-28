# ✅ Site da Divino Barbearia — landing page (HTML + SASS + CSS + JS + Vercel)

Um website profissional, responsivo e otimizado para barbearia, desenvolvido com **HTML5**, **SASS/SCSS**, **CSS compilado**, **JavaScript** e **hospedado na Vercel**.
Inclui organização completa de pastas, uso de parciais SASS, assets de imagem e código limpo e modular.

---

## 📋 Funcionalidades do Site

* ✅ Página inicial moderna com banner
* ✅ Menu responsivo com ícones
* ✅ Seções: **Home, Sobre, Serviços e Localização**
* ✅ Efeitos suaves de hover e transições
* ✅ Botão de WhatsApp para agendamentos
* ✅ Integração com Google Maps
* ✅ Estrutura modular com SASS (SCSS)
* ✅ Hospedagem na Vercel com deploy automático

---

## 🎨 Estrutura SASS (SCSS)

O projeto utiliza **SASS** para organizar os estilos de forma modular e eficiente.

### 📁 Pastas e Arquivos SASS

```
/sass
 ├── style.scss          ← Arquivo principal que importa os parciais
 ├── colors.scss         ← Variáveis de cores, paleta visual
 ├── header.scss         ← Estilos do cabeçalho e menu
 ├── layout.scss         ← Estrutura geral, grids, margens, seções
 └── partials/           ← Arquivos SCSS adicionais
```

### 🧩 Como o SASS funciona no projeto

O arquivo **style.scss** importa todos os outros:

```
@import "colors";
@import "header";
@import "layout";
```

E a compilação gera:

```
style.css
style.css.map
```

Esses são os arquivos lidos pelo navegador.

---

## 🗂️ Estrutura Completa do Projeto

```
/ (raiz do projeto)
│
├── index.html                 ← Página principal do site
│
├── css/
│    ├── style.css             ← CSS compilado
│    ├── style.css.map         ← Mapa de compilação
│    └── style.scss            ← Arquivo SASS principal
│
├── sass/
│    ├── partials/
│    ├── colors.scss
│    ├── header.scss 
│    └── layout.scss
│
├── js/
│    └── script.js             ← animações
├── assets/
│    ├── img/                  ← Imagens do site
│    └── icons/                ← Ícones do menu e seções
│
└── public/
     └── sitemap.xml           ← (opcional, usado para SEO)
```

---

## 🚀 Como Compilar o SASS

### 1️⃣ Instalar o SASS globalmente

```
npm install -g sass
```

### 2️⃣ Compilar automaticamente

```
sass css/style.scss css/style.css --watch
```

---

## 🌍 Hospedagem na Vercel

O site está hospedado na **Vercel**, garantindo:

✔ Deploy automático a cada alteração
✔ HTTPS gratuito
✔ URL pública
✔ Performance otimizada

---

## 🔍 SEO Básico Implementado

* 📌 `<title>` configurado
* 📌 `<meta name="description">`
* 📌 ALT nas imagens
* 📌 Compatibilidade com Google Search Console
* 📌 Possibilidade de sitemap.xml

---

## 📁 Descrição dos Arquivos Principais

### 📝 index.html

Estrutura principal do site, contendo:

* header
* seções
* footer
* links para CSS e JS

### 🎨 style.scss (raiz SASS)

Importa todos os módulos de estilo.

### 🎨 colors.scss

Variáveis como:

```
$primary: #111;
$secondary: #c59d5f;
$bg: #f4f4f4;
```

### 🎨 header.scss

Estiliza:

* menu
* comportamento do scroll
* ícones

### 🎨 layout.scss

Define:

* grid
* espaçamento
* responsividade

### ⚙ script.js

Controla:

* abertura/fechamento do menu
* efeitos visuais
* scroll suave

---

## 👨‍💻 Autor

**Guilherme Guimarães**
Projeto criado para fins educacionais e demonstração profissional de HTML, CSS, SASS, JavaScript e deploy com Vercel.
