<h1 align="center"> QA Portfólio - Testes de Software</h1>

<p align="justify"> Bem-vindo ao meu portfólio de testes de software! Aqui você encontrará uma coleção organizada e prática de testes manuais, testes automatizados e testes de API, utilizando as principais ferramentas do mercado. O objetivo deste repositório é demonstrar minhas habilidades em qualidade de software e automação de testes, seguindo boas práticas e frameworks modernos. Se você é recrutador, desenvolvedor ou profissional de QA, fique à vontade para explorar o conteúdo e trocar experiências!</>



<h1 align="center"> 🛠 Tecnologias & Ferramentas</h1>

<p align="center">
  <a href="https://go-skill-icons.vercel.app/">
    <img
      src="https://go-skill-icons.vercel.app/api/icons?i=cypress,playwright,selenium,postman,javascript,java,git,gherkin,githubactions,github,gitlab,sonarqube"
    />
  </a>
</p>

## Repositório

<details>
<summary>Manual-tests(🚧 Em Construção)</summary>
<br>

*  Testes manuais (documentação, casos de teste, checklist, relatórios)
</details>

<details>
<summary>API-tests(🚧 Em Construção)</summary>
<br>

*  (Testes de API com Postman, Insomnia e automação)
  
</details>
  
<details>
<summary>Automação de testes organizados por framework</summary>
<br>

<details>
<summary>Cypress</summary>

<br>

  🚀 Testes de Automação com Cypress
📌 O que é Cypress?
O Cypress é um framework moderno de automação de testes end-to-end para aplicações web. Ele é conhecido por sua facilidade de configuração, execução rápida e integração nativa com JavaScript. Diferente de outras ferramentas, o Cypress roda diretamente no navegador, permitindo um melhor controle sobre a aplicação testada e facilitando a depuração.

<br>
  
| Vantagem | Descrição |
|----------|----------|
| ✅ Execução rápida | Testes automatizados confiáveis e rápidos |
| ✅ Suporte a JS/TS | Compatível com JavaScript e TypeScript |
| ✅ Depuração avançada | Time-travel, logs detalhados e ferramentas integradas |
| ✅ CI/CD | Fácil integração com pipelines de CI/CD |

<br>
🚀 Instalação do Cypress
O Cypress pode ser instalado de diferentes formas, dependendo do seu ambiente e necessidades. A seguir, apresento um passo a passo para instalar e configurar o Cypress corretamente.

🛠️ Pré-requisitos
Antes de instalar o Cypress, certifique-se de que possui os seguintes requisitos instalados:

✅ Node.js (Versão recomendada: LTS) → [Baixar aqui](https://nodejs.org/pt/download) <br>
✅ Gerenciador de Pacotes (npm ou yarn) (já vem com o Node.js) <br>
✅ Git (opcional, mas recomendado) → [Baixar aqui](https://git-scm.com/downloads) <br>

  <br>

# 🏗️ 1. Criando um novo projeto (caso não tenha um)


  ```
  mkdir meu-projeto-cypress
  cd meu-projeto-cypress
  npm init -y
  ```
# Isso criará um arquivo package.json básico para gerenciar as dependências.

# 📦 2. Instalando o Cypress
🔹 Opção 1: Instalação via npm (Recomendada) <br>
    No diretório do projeto, execute: <br>
  ```
  npm install cypress --save-dev
  ```
🔹 Após a instalação, o Cypress será adicionado às dependências do seu projeto. <br>

# 🚀 3. Abrindo o Cypress pela primeira vez <br>
🔹 Após a instalação, inicie o Cypress com: <br>
```
npx cypress open
```
Modo interativo (com interface gráfica)

```
npx cypress run
```
Modo headless (sem interface gráfica, útil para CI/CD)

# 📂 4. Estrutura de Arquivos do Cypress
Ao executar o Cypress pela primeira vez, ele criará automaticamente a seguinte estrutura dentro do seu projeto <br>

```
📁 cypress/
 ├── 📂 e2e/            # Pasta onde ficam os testes automatizados
 ├── 📂 fixtures/       # Arquivos JSON para simular dados de resposta
 ├── 📂 support/        # Arquivos auxiliares (comandos, hooks, etc.)
 ├── 📂 downloads/      # Para arquivos baixados nos testes
 ├── 📂 screenshots/    # Capturas de tela dos testes
 ├── 📂 videos/         # Gravações automáticas dos testes
📄 cypress.config.js      # Arquivo de configuração do Cypress
```
⚠️ **Atenção:** O Cypress já vem com uma configuração de pasta porém pode ser alterada de acordo com projeto ou da melhor forma que a organização facilite os testes.

# ⚙️ 5. Configurando o Cypress (Opcional)

🔹 O arquivo cypress.config.js permite personalizar diversas opções. Exemplo de configuração básica <br>
```
const { defineConfig } = require('cypress');

module.exports = defineConfig({
  e2e: {
    baseUrl: 'https://meusite.com', // URL base para os testes
    viewportWidth: 1280,
    viewportHeight: 720,
  },
});
```
⚠️ **Atenção:** No arquivo cypress.config.js nesse bloco que se confugura também a parte do relatorios e demais configurações que agregam no cypress. <br>

# 🧪 6. Criando um Primeiro Teste
Agora, crie um teste simples dentro da pasta cypress/e2e/

📄 Arquivo: cypress/e2e/meuTeste.cy.js
```
describe('Meu Primeiro Teste', () => {
  it('Visita a página inicial e verifica o título', () => {
    cy.visit('/');
    cy.contains('Example Domain'); // Verifica se a página contém esse texto
  });
});
```

🎯 Conclusão
Agora você tem o Cypress instalado e configurado no seu projeto! 🚀 Você pode explorar mais funcionalidades como:

Uso de comandos customizados (cypress/support/commands.js)
Configuração de variáveis de ambiente
Integração com CI/CD
Relatórios de testes
Para mais detalhes, consulte a [documentação oficial.](https://docs.cypress.io/app/get-started/why-cypress)

# 📁 Abaixo está projetos que fiz com cypress onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1° - Cypress](https://github.com/heyMichaelS/cypress_pratica)
* [Projeto 2° - Cypress](https://github.com/heyMichaelS/cypress-auth-project)
* [Projeto 3° - Cypress](https://github.com/heyMichaelS/cypress_api/tree/master)
* [Projeto 4° - Cypress](https://github.com/heyMichaelS/cypress_automacao_web)
* [Projeto 5° - Cypress](https://github.com/heyMichaelS/cypress_bdd)
</details>

<details>
<summary>Playwright</summary>
   <br>
🎭 Playwright - Automação de Testes Moderna
O Playwright é um framework de automação de testes de código aberto, desenvolvido pela Microsoft, que permite testar aplicativos da web em múltiplos navegadores (Chromium, Firefox e WebKit) de forma rápida e confiável. Ele suporta testes headless e com interface gráfica, além de oferecer APIs poderosas para interagir com elementos, simular dispositivos móveis, capturar screenshots e muito mais.

 <br>
  <br>

🔹 Principais recursos do Playwright:  <br>
✅ Suporte a múltiplos navegadores: Chromium, Firefox e WebKit <br>
✅ Execução paralela de testes para maior desempenho  <br>
✅ Automação confiável com controle avançado de rede e interceptação de requisições  <br>
✅ Testes de API integrados, permitindo validar backends   <br>
✅ Suporte a linguagens modernas como JavaScript, TypeScript, Python, Java e C#  <br>
✅ Simulação de dispositivos móveis e configurações avançadas  <br>

Com o Playwright, é possível criar testes robustos e escaláveis para validar a experiência do usuário em diferentes cenários, garantindo maior qualidade e confiabilidade no desenvolvimento de aplicações web. 🚀

🎭 Tutorial de Instalação e Configuração do Playwright
O Playwright é um framework moderno para automação de testes, desenvolvido pela Microsoft. Ele permite testar aplicativos da web em múltiplos navegadores (Chromium, Firefox e WebKit), garantindo confiabilidade, velocidade e flexibilidade.


🛠️ 1. Pré-requisitos
Antes de instalar o Playwright, certifique-se de que possui os seguintes requisitos:

✅ Node.js (Versão recomendada: LTS) → [Baixar aqui](https://nodejs.org/pt/download) <br>
✅ Gerenciador de pacotes (npm, yarn ou pnpm)) <br>
✅ Git (opcional, mas recomendado) → [Baixar aqui](https://git-scm.com/downloads)  <br>


📦 2. Criando um Novo Projeto
Se ainda não tiver um projeto Node.js, crie um diretório e inicialize o projeto:

```
mkdir meu-projeto-playwright
cd meu-projeto-playwright
```
🔹 Isso criará um arquivo package.json para gerenciar as dependências.

📥 3. Instalando o Playwright  <br>
🔹 Opção 1: Instalação via npm (Recomendada) <br>
```
npm init playwright@latest
```
📝 4. Criando um Teste Automatizado
Agora, crie um arquivo de teste dentro da pasta tests/:

📄 Arquivo: tests/example.test.js

```
import { test, expect } from '@playwright/test';

test('Verificar título da página', async ({ page }) => {
  await page.goto('https://playwright.dev/'); // Abre o site
  const title = await page.title(); // Obtém o título da página
  expect(title).toBe('Fast and reliable end-to-end testing for modern web apps | Playwright'); // Valida o título
});

```
▶️ 6. Executando os Testes
* Para rodar `todos os testes:`
  
```
npx playwright test
```

Para rodar um `teste específico:`
```
npx playwright test tests/example.test.js
```

Para rodar os testes `com interface gráfica (UI Mode):`
```
npx playwright test --ui
```

Para rodar os testes `em modo headless (sem interface gráfica):`
```
npx playwright test --headless
```
📊 7. Gerando Relatórios de Teste
O Playwright inclui suporte nativo para relatórios de teste. Após a execução, os resultados ficam armazenados na pasta playwright-report/.

Para abrir o relatório interativo, use:
```
npx playwright show-report
```
🎯 Conclusão
Agora você tem um ambiente configurado para automação de testes com Playwright! 🚀

✅ Instalação e configuração
✅ Criação de testes automatizados
✅ Execução e geração de relatórios
  
📌 Para mais detalhes, consulte a [documentação oficial.](https://playwright.dev/docs/intro)

# 📁 Abaixo está projetos que fiz com cypress onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1° - Playwright](https://github.com/heyMichaelS/automacao_web_playwright)
* [Projeto 2° - Playwright](https://github.com/heyMichaelS/playwright_api)



</details>

<details>
<summary>Codeceptjs</summary>

<br>
🚀 Instalação e Configuração do CodeceptJS para Testes de API
O CodeceptJS é um framework moderno para automação de testes end-to-end, suportando diversos drivers como Playwright, WebDriver, Puppeteer e TestCafe. Além disso, permite a execução de testes de API, tornando-se uma ferramenta versátil para diferentes cenários de testes.
<br>

🛠️ Pré-requisitos
Antes de instalar o CodeceptJS, verifique se possui os seguintes requisitos:

✅ Node.js (Versão recomendada: LTS) → [Baixar aqui](https://nodejs.org/pt/download) <br>
✅ Gerenciador de Pacotes (npm ou yarn) (já vem com o Node.js) <br>
✅ Git (opcional, mas recomendado) → [Baixar aqui](https://git-scm.com/downloads) <br>

<br>

# 🏗️ 1. Criando um Novo Projeto
Se ainda não tiver um projeto Node.js, crie um diretório e inicialize o projeto:

```
mkdir meu-projeto-codecept
cd meu-projeto-codecept
npm init -y
```
Isso criará um arquivo package.json básico para gerenciar as dependências.

# 📦 2. Instalando o CodeceptJS
🔹 Opção 1: Instalação via npm (Recomendada)

```
npm install codeceptjs --save-dev
```
# ⚙️ 3. Inicializando o CodeceptJS

```
npx codeceptjs init
```
🔹 Durante a configuração interativa, o CodeceptJS fará algumas perguntas sobre o ambiente de testes, como:

* Qual helper usar? (Selecione REST para testes de API) <br>
* Onde salvar os testes? (Padrão: ./tests) <br>
* Qual formato de saída do relatório? (Escolha um, como Mocha) <br>
🔹 Isso criará automaticamente o arquivo de configuração codecept.conf.js. <br>


# 🔧 4. Configurando o CodeceptJS para Testes de API

🔹 Edite o arquivo codecept.conf.js para incluir a configuração de API Testing com REST:

📄 Arquivo: codecept.conf.js

```
const { setHeadlessWhen } = require('@codeceptjs/configure');

setHeadlessWhen(process.env.HEADLESS);

exports.config = {
  tests: './tests/api/*_test.js',  // Define onde os testes serão salvos
  output: './output',              // Pasta de saída para logs e screenshots
  helpers: {
    REST: {                        // Ativa o helper REST para testes de API
      endpoint: 'https://jsonplaceholder.typicode.com',  // URL base da API
      onRequest: (request) => {
        request.headers.auth = 'Bearer token_aqui';  // Adiciona autenticação (se necessário)
      }
    }
  },
  include: {},
  bootstrap: null,
  mocha: {},
  name: 'meu-projeto-codecept'
};
```
⚠️ **Atenção:**  A configuração pode ter diferentes modificações dependendo do projeto acima é somente uma base de exemplo.

# 🧪 5. Criando um Teste de API
🔹 Agora, crie um teste simples dentro da pasta tests/api/:

📄 Arquivo: tests/api/users_test.js

```
Feature('Users API');

Scenario('Deve buscar a lista de usuários', async ({ I }) => {
  const response = await I.sendGetRequest('/users');

  // Verifica se a resposta tem status 200
  I.seeResponseCodeIs(200);

  // Valida se a resposta contém uma lista de usuários
  I.seeResponseContainsJson([{ id: 1 }]);
});

Scenario('Deve criar um novo usuário', async ({ I }) => {
  const response = await I.sendPostRequest('/users', {
    name: 'João Silva',
    username: 'joaosilva',
    email: 'joao@email.com'
  });

  // Verifica se o status de resposta é 201 (Criado)
  I.seeResponseCodeIs(201);

  // Valida se o nome do usuário criado está na resposta
  I.seeResponseContainsJson({ name: 'João Silva' });
});
```
# ▶️ 6. Executando os Testes
🔹Para rodar todos os testes

```
npx codeceptjs run --steps
```
🔹 Para rodar um teste específico
```
npx codeceptjs run --grep "@@sucesso"
```

🔹 Estrutura Exemplo do Teste Abaixo

```
Feature('login');

Scenario('Login com sucesso ', async ({ I }) => {

    I.amOnPage('https://automationpratice.com.br/')
    I.click('Login')
    I.waitForText('Login', 15)
    I.fillField('#user', 'teste@teste.com')
    I.fillField('#password', '12345678')
    I.click('#btnLogin')
    I.waitForText('Login realizado', 3)

}).tag('@sucesso')

```

🔹Para rodar os testes em modo interativo

```
npx codeceptjs shell
```
A opção --steps exibe o passo a passo da execução.

# 📊 7. Gerando Relatórios de Testes

Para gerar relatórios HTML após a execução, instale o pacote mocha-multi-reporters
```
npm install mocha-multi-reporters --save-dev
```
E adicione a seguinte configuração no codecept.conf.js:

```
mocha: {
  reporterOptions: {
    reportDir: "output"
  }
}
```

# 🎯 Conclusão
Agora você tem um ambiente configurado para testes de API com CodeceptJS! 🚀

✅ Instalação e configuração do framework
✅ Criação de testes automatizados de API
✅ Execução e geração de relatórios

📌 Para mais detalhes, consulte a [documentação oficial.](https://codecept.io/api/#api-testing)
Agora, após executar os testes, o relatório estará disponível na pasta output.

# 📁 Abaixo está projetos que fiz com cypress onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - CodeceptJS](https://github.com/heyMichaelS/CodeceptJs_Projeto_Web/tree/master)
* [Projeto 2º - CodeceptJS](https://github.com/heyMichaelS/Appium_codeceptjs)
* [Projeto 3º - CodeceptJS]()

</details>

<details>
<summary>Selenium</summary>
    <br>  
* Selenium
</details>
  
<details>
<summary>Supertest</summary>

🚀 SuperTest - Testes de API Simples e Eficientes
O SuperTest é uma biblioteca para testes de API em Node.js, projetada para facilitar a verificação de endpoints REST e GraphQL. Ele se integra facilmente com frameworks como Express, Koa e outros, permitindo testar requisições HTTP de maneira simples e intuitiva.

🔹 Principais recursos do SuperTest:  <br>
✅ Facilidade de uso – Sintaxe intuitiva baseada em superagent  <br>
✅ Suporte a testes assíncronos com Promises e async/await  <br>
✅ Integração com Jest, Mocha, Chai e outros frameworks de teste  <br>
✅ Validação de status, cabeçalhos e respostas JSON  <br>
✅ Execução rápida de testes sem precisar iniciar um servidor manualmente <br>

Com o SuperTest, é possível criar testes automatizados eficientes para garantir a qualidade e a confiabilidade de APIs. 🚀

🛠️ Tutorial de Instalação e Configuração do SuperTest
1. Pré-requisitos
Antes de instalar o SuperTest, certifique-se de que possui os seguintes requisitos:



📥 2. Criando um Novo Projeto
Se ainda não tiver um projeto Node.js, crie um diretório e inicialize o projeto:

```
mkdir meu-projeto-supertest
cd meu-projeto-supertest
```

📦 3. Instalando o SuperTest
🔹 Opção 1: Instalação via npm (Recomendada)
```
npm install jest supertest
```
⚙️ 4. Criando um Servidor para Teste
Para exemplificar, vamos criar uma API simples usando Express:
📄 Arquivo: server.js

```
const express = require('express');
const app = express();

app.use(express.json());

app.get('/ping', (req, res) => {
  res.status(200).json({ message: 'pong' });
});

app.post('/echo', (req, res) => {
  res.status(201).json({ data: req.body });
});

module.exports = app;

```

📝 5. Criando Testes com SuperTest
Agora, crie um arquivo para testar a API:

📄 Arquivo: tests/api.test.js

```
const request = require('supertest');
const app = require('../server');

describe('Testes da API', () => {
  test('Deve retornar pong ao acessar /ping', async () => {
    const response = await request(app).get('/ping');
    expect(response.status).toBe(200);
    expect(response.body).toEqual({ message: 'pong' });
  });

  test('Deve retornar os dados enviados via POST em /echo', async () => {
    const payload = { nome: 'QA Tester' };
    const response = await request(app).post('/echo').send(payload);
    
    expect(response.status).toBe(201);
    expect(response.body).toEqual({ data: payload });
  });
});

```

▶️ 6. Executando os Testes
Se estiver usando Jest, adicione o seguinte script no package.json:

📄 Arquivo: package.json
```
"scripts": {
  "test": "jest"
}
```
Agora, execute os testes com:

```
npm test
```

📊 7. Relatórios de Testes
Para gerar um relatório detalhado, use a flag --coverage:

```
npm test -- --coverage
```

📌 Para mais detalhes, consulte a [documentação oficial.](https://www.npmjs.com/package/supertest) <br>

✅ Node.js (Versão recomendada: LTS) → [Baixar aqui](https://nodejs.org/pt/download) <br>
✅ Gerenciador de pacotes (npm, yarn ou pnpm) <br>
✅ Git (opcional, mas recomendado) → [Baixar aqui](https://git-scm.com/downloads)

# 📁 Abaixo está projetos que fiz com cypress onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - Superset]([https://github.com/heyMichaelS/CodeceptJs_Projeto_Web/tree/master](https://github.com/heyMichaelS/supertest_api))

```

```

```

```

</details>
</details>

  
<details>
<summary>Performance-tests(🚧 Em Construção)</summary>
<br>

<details>
  <summary>JMeter</summary>

* JMeter
  </details>

<details>
<summary>k6</summary>

* k6
  
</details>
</details>

<details>
<summary>Security-tests(🚧 Em Construção)</summary>
<br>
*  (Rpositorio em construção)
</details>



<div align="center">

## Contatos:

<div>
<a href = "https://github.com/heyMichaelS"><img loading="lazy" src= "https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white"  target="_blank"></a>
<a href = "https://linkedin.com/in/heymichaels" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  
<a href = "https://michaelfelipe180@gmail.com"><img loading="lazy" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href = "https://www.instagram.com/michaeeltyr/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>

 
</div>
