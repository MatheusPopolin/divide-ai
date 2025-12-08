# 💸 DivideAí

## 👤 Identificação/Autor

**Aluno:** Matheus Popolin

---

## 📌 Descrição do Projeto

O **DivideAí** é uma aplicação web para auxiliar pessoas a dividir despesas em grupo de forma justa e organizada.  
O usuário poderá cadastrar participantes, lançar despesas indicando quem pagou e para quem será dividida a cobrança, e visualizar os cálculos de quanto cada pessoa deve ou tem a receber.

---

## 🎨 Prototipação no Figma

[Figma](https://www.figma.com/design/J5kJCKGdkKwLVWtCR2KNTW/Divide-A%C3%AD?node-id=6488-1727&p=f&t=gBHL9xUY8mVu0Vm9-0)

---

## 🖌️ Design System

[Link para o documento de Design System](https://docs.google.com/document/d/1CsG8j5hFIWEHodd60_FJ6cpbnJy7Zt21KoNE-R_BpoI/edit?usp=sharing)

---

## 🎨 Framework CSS

- **Bootstrap**

---

## 📦 Dependências

- JavaScript nativo (ES6+)
- [JSON Server](https://github.com/typicode/json-server) _(para API fake)_
- [jQuery](https://jquery.com/) _(para manipulação do DOM e interatividade, opcional)_
- [jQuery Mask Plugin](https://igorescobar.github.io/jQuery-Mask-Plugin/) _(utilizado para mascarar campos, ex: CPF, telefone, etc, caso necessário)_
- [Bootstrap](https://getbootstrap.com/) _(CSS e JS, para componentes e interatividade)_
- [Popper.js](https://popper.js.org/) _(usado em conjunto com o Bootstrap para tooltips, popovers, etc)_

---

## 🌐 Site em Produção

[DivideAí no GitHub Pages](https://matheuspopolin.github.io/divide-ai/)

---

## ✅ Checklist de Funcionalidades


- [x] Cadastro de participantes
- [x] Registro de despesas
- [x] Cálculo automático de quanto cada pessoa deve/paga
- [x] Listagem de despesas em cards
- [x] Persistência de dados no `localStorage`
- [x] Integração com **JSON Server** para persistência de dados
- [x] Validação de formulários (HTML + JS)
- [x] Layout responsivo (mobile e desktop)
- [x] Utilização de componentes prontos do framework CSS

---

## 🚀 Instruções de Execução

### 🔹 Pré-requisitos

- [Node.js](https://nodejs.org/) instalado
- [JSON Server](https://github.com/typicode/json-server) instalado globalmente ou via `npm install json-server --save-dev`

### 🔹 Passos

1. Clone este repositório:

   ```bash
   git clone https://github.com/matheuspopolin/divideai.git
   cd divideai
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o JSON Server:

   ```bash
   cd server
   npx json-server --watch db.json --port 3000
   ```

4. Abra o arquivo `index.html` no navegador ou utilize uma extensão como **Live Server** no VS Code.

---

## 🖼️ Telas da Aplicação

_(Screenshots das telas desenvolvidas serão adicionados aqui)_

---

## 📖 Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

A aplicação deve ser implementada contendo as funcionalidades referentes aos tópicos apresentados a seguir estruturados de acordo com os Resultados de Aprendizagem da Matriz por Competências.

### RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos

- [x] ID 01 - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
- [x] ID 02 - Implementa layout responsivo com Framework CSS (Bootstrap, Materialize, Tailwind + DaisyUI) usando Flexbox ou Grid do próprio framework.
- [x] ID 03 - Implementa layout responsivo com CSS puro, usando Flexbox ou Grid Layout.
- [x] ID 04 - Utiliza componentes prontos de um Framework CSS (ex.: card, button) e componentes JavaScript do framework (ex.: modal, carousel).
- [x] ID 05 - Cria layout fluido usando unidades relativas (vw, vh, %, em, rem) no lugar de unidades fixas (px).
- [x] ID 06 - Aplica um Design System consistente (cores, tipografia, padrões de componentes) em toda a aplicação.
- [x] ID 07 - Utiliza pré-processadores CSS (Sass, SCSS) com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.
- [x] ID 08 - Aplica tipografia responsiva (media queries mobile first) ou tipografia fluida (função clamp() + unidades relativas).
- [] ID 09 - Aplica técnicas de responsividade de imagens usando CSS (object-fit, containers com unidades relativas).
- [] ID 10 - Otimiza imagens usando formatos modernos (WebP) e carregamento adaptativo (srcset, picture, ou parâmetros do Cloudinary).

### RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente

- [x] ID 11 - Implementa validação HTML nativa (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.
- [x] ID 12 - Aplica expressões regulares (REGEX) para validações customizadas (e-mail, telefone, datas, etc.).
- [x] ID 13 - Utiliza elementos de seleção em formulários (checkbox, radio, select) para coleta de dados.
- [x] ID 14 - Implementa leitura e escrita no Web Storage (localStorage/sessionStorage) para persistir dados localmente.

### RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web

- [x] ID 15 - Configura ambiente com Node.js e NPM para gerenciamento de pacotes e dependências.
- [x] ID 16 - Utiliza boas práticas de versionamento no Git/GitHub (branch main ou branches específicos, uso de .gitignore).
- [x] ID 17 - Mantém um README.md padronizado, conforme template da disciplina, com checklist preenchido.
- [] ID 18 - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
- [x] ID 19 - Configura linters e formatadores (ESLint, Prettier) para manter qualidade e padronização do código.

### RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web

- [x] ID 20 - Utiliza jQuery para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).
- [x] ID 21 - Integra e configura um plugin jQuery relevante (ex.: jQuery Mask Plugin).

### RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente

- [x] ID 22 - Realiza requisições assíncronas para uma API fake (ex.: JSON Server) para persistir dados de um formulário.
- [x] ID 23 - Realiza requisições assíncronas para uma API fake para exibir dados na página.
- [] ID 24 - Realiza requisições assíncronas para APIs públicas reais (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.
