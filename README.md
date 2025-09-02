# 💸 DivideAí

## 👤 Identificação/Autor
**Aluno:** Matheus Popolin  

---

## 📌 Descrição do Projeto
O **DivideAí** é uma aplicação web para auxiliar pessoas a dividir despesas em grupo de forma justa e organizada.  
O usuário poderá cadastrar participantes, lançar despesas indicando quem pagou e para quem será dividida a cobrança, e visualizar os cálculos de quanto cada pessoa deve ou tem a receber.  

---

## 🎨 Prototipação no Figma
[Figma](https://www.figma.com/design/OKYROVPyDKFA8HdsYDoStN/Divide-A%C3%AD?t=A6lNWIiGrLsfbSCH-1) *(em andamento)*  

---

## 🖌️ Design System
[Link para o documento de Design System](#) *(a ser adicionado)*  

---

## 🎨 Framework CSS
- **Bootstrap** *(ou Tailwind/DaisyUI, a ser decidio)*  

---

## 📦 Dependências
- JavaScript nativo (ES6+)  
- [JSON Server](https://github.com/typicode/json-server) *(para API fake)*  
- [jQuery](https://jquery.com/) *(para manipulação do DOM e interatividade, opcional)*  
- Plugins adicionais (ex.: jQuery Mask Plugin) *(a definir)*  

---

## 🌐 Site em Produção
[DivideAí no GitHub Pages](#) *(a ser adicionado após deploy)*  

---

## ✅ Checklist de Funcionalidades
(a ser decidido)
- [ ] Cadastro de participantes  
- [ ] Registro de despesas  
- [ ] Cálculo automático de quanto cada pessoa deve/paga  
- [ ] Listagem de despesas em tabela/cards  
- [ ] Persistência de dados no `localStorage`  
- [ ] Integração com **JSON Server** para persistência de dados  
- [ ] Validação de formulários (HTML + JS)  
- [ ] Layout responsivo (mobile e desktop)  
- [ ] Utilização de componentes prontos do framework CSS  

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

2. Instale as dependências (se houver):
   ```bash
   npm install
   ```

3. Inicie o JSON Server:
   ```bash
   npx json-server --watch db.json --port 3000
   ```

4. Abra o arquivo `index.html` no navegador ou utilize uma extensão como **Live Server** no VS Code.  

---

## 🖼️ Telas da Aplicação
*(Screenshots das telas desenvolvidas serão adicionados aqui)*  

---

## 📖 Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

A aplicação deve ser implementada contendo as funcionalidades referentes aos tópicos apresentados a seguir estruturados de acordo com os Resultados de Aprendizagem da Matriz por Competências. 

### RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos
- [ ] ID 01 - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).  
- [ ] ID 02 - Implementa layout responsivo com Framework CSS (Bootstrap, Materialize, Tailwind + DaisyUI) usando Flexbox ou Grid do próprio framework.  
- [ ] ID 03 - Implementa layout responsivo com CSS puro, usando Flexbox ou Grid Layout.  
- [ ] ID 04 - Utiliza componentes prontos de um Framework CSS (ex.: card, button) e componentes JavaScript do framework (ex.: modal, carousel).  
- [ ] ID 05 - Cria layout fluido usando unidades relativas (vw, vh, %, em, rem) no lugar de unidades fixas (px).  
- [ ] ID 06 - Aplica um Design System consistente (cores, tipografia, padrões de componentes) em toda a aplicação.  
- [ ] ID 07 - Utiliza pré-processadores CSS (Sass, SCSS) com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.  
- [ ] ID 08 - Aplica tipografia responsiva (media queries mobile first) ou tipografia fluida (função clamp() + unidades relativas).  
- [ ] ID 09 - Aplica técnicas de responsividade de imagens usando CSS (object-fit, containers com unidades relativas).  
- [ ] ID 10 - Otimiza imagens usando formatos modernos (WebP) e carregamento adaptativo (srcset, picture, ou parâmetros do Cloudinary).  

### RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente
- [ ] ID 11 - Implementa validação HTML nativa (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.  
- [ ] ID 12 - Aplica expressões regulares (REGEX) para validações customizadas (e-mail, telefone, datas, etc.).  
- [ ] ID 13 - Utiliza elementos de seleção em formulários (checkbox, radio, select) para coleta de dados.  
- [ ] ID 14 - Implementa leitura e escrita no Web Storage (localStorage/sessionStorage) para persistir dados localmente.  

### RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web
- [ ] ID 15 - Configura ambiente com Node.js e NPM para gerenciamento de pacotes e dependências.  
- [ ] ID 16 - Utiliza boas práticas de versionamento no Git/GitHub (branch main ou branches específicos, uso de .gitignore).  
- [ ] ID 17 - Mantém um README.md padronizado, conforme template da disciplina, com checklist preenchido.  
- [ ] ID 18 - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.  
- [ ] ID 19 - Configura linters e formatadores (ESLint, Prettier) para manter qualidade e padronização do código.  

### RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web
- [ ] ID 20 - Utiliza jQuery para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).  
- [ ] ID 21 - Integra e configura um plugin jQuery relevante (ex.: jQuery Mask Plugin).  

### RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente
- [ ] ID 22 - Realiza requisições assíncronas para uma API fake (ex.: JSON Server) para persistir dados de um formulário.  
- [ ] ID 23 - Realiza requisições assíncronas para uma API fake para exibir dados na página.  
- [ ] ID 24 - Realiza requisições assíncronas para APIs públicas reais (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.  
