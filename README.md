# 📈 Sistema de Cadastro de Negociações (TypeScript)

Este projeto é uma aplicação web desenvolvida com **TypeScript** para cadastrar e importar negociações financeiras. Foi criado como parte da formação em TypeScript oferecida pela **Alura**, com o objetivo de praticar conceitos fundamentais da linguagem e sua aplicação em projetos reais.

---

## 🌐 Funcionalidades

- Cadastro de negociações com **data**, **quantidade** e **valor**;
- Listagem de negociações adicionadas manualmente;
- **Importação** de negociações via API;
- Utilização de recursos modernos do TypeScript como:
  - `strictNullChecks`
  - `experimentalDecorators`
  - `sourceMap`

---

## 📁 Estrutura do Projeto

```
📂 negociacoesTypeScript
├️📁 app/                  # Código-fonte da aplicação
├️📁 servidor-api/         # Backend fake para importação de dados
├️📁 dist/                 # Arquivos compilados
├️ tsconfig.json         # Configurações do compilador TypeScript
├️ package.json          # Dependências e scripts do projeto
└️ README.md             # Documentação do projeto
```

---

## 🚀 Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/brunodomingues98/negociacoesTypeScript.git
   cd negociacoesTypeScript
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Compile o TypeScript:**
   ```bash
   tsc
   ```

4. **Inicie o servidor da API fake:**
   ```bash
   cd servidor-api
   npm install
   npm start
   ```

5. **Abra o `index.html` no navegador:**
   Basta abrir o arquivo `index.html` dentro da pasta `dist` com o navegador de sua preferência.

---

## 📄 Tecnologias utilizadas

- TypeScript
- HTML5
- JavaScript (compilado do TS)
- Node.js (para simular API)

---

## 💡 Aprendizados

Durante o desenvolvimento foram aplicados e fixados os seguintes conceitos:

- Tipagem estática e segura com TypeScript
- Organização de código em módulos e classes
- Uso de decorators
- Manipulação do DOM via TypeScript
- Boas práticas de desenvolvimento frontend

---

## 📖 Créditos

Projeto baseado na formação [TypeScript na Prática](https://www.alura.com.br/) da plataforma Alura.

---

## 📅 Licença

Este projeto tem fins educacionais e está aberto para consulta e aprendizado.

---

🚀 Explore, aprenda e contribua!

