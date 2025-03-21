<h1 align="center"> QA Portfólio - Testes de Software</h1>

<p align="justify"> Bem-vindo ao meu portfólio de testes de software! Aqui você encontrará uma coleção organizada e prática de testes manuais, testes automatizados e testes de API, utilizando as principais ferramentas do mercado. O objetivo deste repositório é demonstrar minhas habilidades em qualidade de software e automação de testes, seguindo boas práticas e frameworks modernos. Se você é recrutador, desenvolvedor ou profissional de QA, fique à vontade para explorar o conteúdo e trocar experiências!</>

📌 Quem Sou Eu
Olá! 👋 Me chamo Michael Felipe e sou QA Engineer com experiência em testes manuais e automação. Minha missão é garantir a qualidade do software através de estratégias eficazes de testes, automação robusta e uma forte cultura de qualidade.

🚀 Minha Jornada
Desde o início da minha carreira, venho aprimorando minhas habilidades em testes de software, passando por áreas como:

`Testes Manuais 📝` (Caixa Branca, Caixa Preta, Regressão, Exploratório) <br>

`Automação de Testes 🤖` (Cypress, Selenium, Playwright, Appium, Robot Framework)  <br>

`Teste Mobile 🤖` (Appium , Maestro , Expresso - Android) <br>

`Testes de API 🔗` (Postman, Supertest, CodeceptJS, REST Assured)  <br>

`Testes de Performance ⚡` (JMeter, K6, Wiremock)  <br>

`Integração Contínua (CI/CD) 🔄` (GitHub Actions, Jenkins, GitLab CI)  <br>

Com uma formação em Banco de Dados pela FATEC, também tenho experiência com SQL e manipulação de dados, o que me ajuda a validar integrações e estruturar testes mais robustos.  <br>

💡 O Que Você Vai Encontrar Neste Portfólio?
Aqui, compartilho projetos práticos que mostram minha experiência em automação de testes, testes de API, mobile e performance. Meu objetivo é criar um repositório vivo de aprendizado e evolução na área de QA.

🎯 Busco Sempre Evoluir!
Estou sempre estudando novas tecnologias e aprimorando minhas habilidades. Atualmente, estou aprofundando meus conhecimentos em Appium, ALM Octane e Mobile Center para expandir minha atuação na área de qualidade de software.



<h1 align="center"> 🛠 Tecnologias & Ferramentas</h1>

<p align="center">
  <a href="https://go-skill-icons.vercel.app/">
    <img
      src="https://go-skill-icons.vercel.app/api/icons?i=cypress,playwright,selenium,postman,javascript,java,git,gherkin,githubactions,github,gitlab,sonarqube"
    />
  </a>
</p>

## Repositórios

<details>
<summary>Manual-tests(🚧 Em Construção)</summary>
<br>


*  Testes manuais (documentação, casos de teste, checklist, relatórios)
</details>

<details>
<summary>API-tests</summary>
<br>

<details>
<summary>Postman + Newman</summary>

# Nesse estudo eu vou postar alguns prints de como foi feito os testes no postaman e de como usei o newman pra complementar

# 1-Passo configurei a url base

<p align="center"><img src=https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20111409.png  alt="Sua Foto" width="800" height="500"/>


# 2-Coloquei no script de teste para gerar um email diferente sempre que preenchido 
<p align="center"><img src=https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20111615.png alt="Sua Foto" width="800" height="500"/>

* 2.1 Response
 <p align="center"><img src=https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20111632.png alt="Sua Foto" width="800" height="500"/>

* 2.2 O email foi alterado por uma variávei de ambiente para aceitar a condição do script "{{ }}"
<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20111748.png alt="Sua Foto" width="800" height="500"/>

# 3-Register a user an invalid password
<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112540.png alt="Sua Foto" width="800" height="500"/>

* 3.1 Body
<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112553.png alt="Sua Foto" width="800" height="500"/>

# 4-Autenticar um usuario 

<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112654.png alt="Sua Foto" width="800" height="500"/>

* 4.1 Body

<p align="center"><img src=https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112706.png alt="Sua Foto" width="800" height="500"/>

# 5-Registrar um post 

<p align="center"><img src=https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112739.png alt="Sua Foto" width="800" height="500"/>

* 5.1 Body
 <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112750.png alt="Sua Foto" width="800" height="500"/>

* 5.2 Configuração do Baren Token 
 <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112801.png alt="Sua Foto" width="800" height="500"/>

 
# 6-Retrivies

 <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20112852.png alt="Sua Foto" width="800" height="500"/>

# 7-Delete um post

 <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20113000.png alt="Sua Foto" width="800" height="500"/>

* 7.1 Como é delete de um post precisa de uma autenticação seguindo a regra da api

  <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20113019.png alt="Sua Foto" width="800" height="500"/>

# 8-Delete sem autenticação nesse caso não é necessário

 <p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-20%20113033.png alt="Sua Foto" width="800" height="500"/>

 # 9-Depois de finalizado consegue fazer o export do json de todo teste e rodar com newman 
 
Para instalar na maquina antes de rodar a collection
```
npm i -g newman
```
Após
```
newman run nome_do-arquivo
```
* 9.1 após instalado no terminal deve ser assim sua visão

<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-19%20034644.png alt="Sua Foto" width="500" height="500"/>

* 9.2 No newman também pode gerar relatorios em html com esse comando

```
npm i -g newman-reporter-htmlextra
```
Após
```
newman run nome_do_arquivo.json -r htmlextra
```
* Irá gerar uma visão assim 
<p align="center"><img src= https://github.com/heyMichaelS/postman-newman/blob/master/imagens/Captura%20de%20tela%202025-02-19%20034602.png alt="Sua Foto" width="800" height="500"/>



# 📁 Abaixo está projetos que fiz com Postman + Newman onde coloquei em prática os ensinamentos de teste<br>

* [Projeto 1° - Postman + Newman](https://github.com/heyMichaelS/postman-newman)

<hr>
</details>
</details>
 
<details>
<summary>Automação de testes organizados por framework Web</summary>

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
 <hr>
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

# 📁 Abaixo está projetos que fiz com Playwright onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1° - Playwright](https://github.com/heyMichaelS/automacao_web_playwright)
* [Projeto 2° - Playwright](https://github.com/heyMichaelS/playwright_api)

<hr>

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

# 📁 Abaixo está projetos que fiz com CodeceptJs onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - CodeceptJS](https://github.com/heyMichaelS/CodeceptJs_Projeto_Web/tree/master)
* [Projeto 2º - CodeceptJS + Appium](https://github.com/heyMichaelS/Automacao_Testes_Mobile_CodeceptJs_Appium))
* [Projeto 3º - CodeceptJS]()
<hr>
</details>

<details>
<summary>Selenium</summary>
    <br>  
* Selenium
</details>

<details>
<summary>Robot Framework</summary>
    <br>  
  
🤖 Introdução ao Robot Framework
O Robot Framework é um framework de automação de testes baseado em palavras-chave (Keyword-Driven Testing) que permite escrever testes de forma intuitiva e legível. Ele é amplamente utilizado para testar APIs, aplicações web, mobile e desktop, suportando bibliotecas como Selenium, Appium, Requests e muitas outras.

🚀 Principais Vantagens do Robot Framework <br>
✅ Fácil de aprender – Utiliza uma sintaxe legível em estilo tabela ou texto <br>
✅ Suporte a múltiplas bibliotecas – Selenium, Appium, API Requests, entre outras <br>
✅ Extensível – Pode ser integrado com Python e Java para personalizar testes <br>
✅ Execução multiplataforma – Roda em Windows, Linux e macOS <br>
✅ Relatórios detalhados – Gera logs e reports automaticamente <br>


🛠 Passo a Passo: Instalando e Configurando o Robot Framework <br>

📌 1. Pré-requisitos <br>
Antes de instalar o Robot Framework, verifique se tem:

✔ Python 3.7 ou superior instalado <br>
✔ pip atualizado <br>
✔ IDE compatível (ex: VS Code, PyCharm ou Robot Framework IDE) <br>

Para verificar o Python e o pip, rode:

```
python --version
pip --version
```
Se o Python não estiver instalado, baixe-o [em:](https://www.python.org/downloads/)

📌 2. Instalando o Robot Framework
<br>
Para instalar o Robot Framework, use o seguinte comando:

```
pip install robotframework-requests
```
No teste que eu fiz usei [RequestLibrary](https://github.com/MarketSquare/robotframework-requests#readme) <br>
Para verificar se a instalação foi bem-sucedida:

```
robot --version
```

Exemplo de Test

```
*** Settings ***
Library    RequestsLibrary

*** Variables ***
${URL_BASE}    https://restful-booker.herokuapp.com

*** Keywords ***


Step 1: Fazer uma request GET para a URL
    ${response}=    GET    ${URL_BASE}/booking
    Log    Response Status: ${response.status_code}
    Log    Response Body: ${response.text}
    [Return]    ${response}

Step 2: Validar status da resposta
    [Arguments]    ${response}
    Status Should Be    200    ${response}

Step 3: Validar corpo da resposta
    [Arguments]    ${response}
    ${response_json}=    Evaluate    json.loads($response.text)    json
    Should Not Be Empty    ${response_json}    A resposta não pode ser vazia!

*** Test Cases ***
Cenário 1: Fazer uma request GET e validar resposta
    ${response}=    Step 1: Fazer uma request GET para a URL
    Step 2: Validar status da resposta    ${response}
    Step 3: Validar corpo da resposta    ${response}

```
📌 5. Executando o Teste
```
 python -m robot nomedoteste.robot

  ou

robot nomedoteste.robot
```

Se quiser salvar os logs e reports em uma pasta específica:

```
robot -d results teste_login.robot
```
Após a execução, os logs e reports serão gerados na pasta results/ e poderão ser abertos no navegador.



É uma ótima opção para equipes que querem uma abordagem mais amigável e reutilizável para a automação de testes.

📌 Para mais detalhes, consulte a [documentação oficial.](https://robotframework.org/) <br>
Agora, após executar os testes, o relatório é gerado na raiz do projeto.

# 📁 Abaixo está projetos que fiz com Robot Framework onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - Robot Framework](https://github.com/heyMichaelS/robot-framework-api)

<hr>
</details>

<details>
<summary>Rest-assured</summary>
    <br>
  
📌 Introdução ao REST-Assured  <br>
O REST-Assured é uma biblioteca Java para testar APIs RESTful de forma simples e intuitiva. Ele facilita a escrita de testes automatizados para serviços web, eliminando a necessidade de lidar diretamente com bibliotecas HTTP complexas.

É amplamente utilizado para automação de testes de API em projetos Java, permitindo validar respostas HTTP, cabeçalhos, status e até mesmo autenticação de APIs.
  
🚀 Principais Vantagens do REST-Assured:  <br>
✅ Sintaxe fluida e fácil de ler  <br>
✅ Suporte nativo para testes de API REST  <br>
✅ Integração com frameworks de teste como JUnit e TestNG  <br>
✅ Suporte a autenticação, parâmetros e validação de JSON/XML  <br>

🛠️ Pré-requisitos <br>
Antes de instalar o REST-Assured, verifique se possui os seguintes requisitos configurados corretamente:  <br>

✔ JetBrains IntelliJ IDEA → [Baixe aqui](https://www.jetbrains.com/idea/download/?section=window) s<br>
✔ Java JDK instalado e configurado (verifique a versão compatível com o projeto) → [Baixe aqui](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html) <br>
✔ Apache Maven instalado e configurado (caso não tenha, baixe e instale) → [Baixe aqui](https://maven.apache.org/download.cgi) <br>


🛠 Tutorial Passo a Passo: Instalação e Configuração
📌 1. Adicionar REST-Assured ao Projeto
Se estiver usando Maven, adicione a seguinte dependência ao pom.xml:


 ```
  <dependencies>
    <dependency>
        <groupId>io.rest-assured</groupId>
        <artifactId>rest-assured</artifactId>
        <version>5.4.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>

  ```
Se estiver usando Gradle, adicione ao build.gradle:
 ```
dependencies {
    testImplementation 'io.rest-assured:rest-assured:5.4.0'
}

  ```
📌 2. Criar um Teste Simples com REST-Assured
Agora, vamos criar um teste para validar um endpoint /ping que retorna um JSON com { "message": "pong" }.

📄 Arquivo: ApiTest.java

  ```
import io.restassured.RestAssured;
import io.restassured.response.Response;
import org.junit.jupiter.api.Test;

import static io.restassured.RestAssured.*;
import static org.hamcrest.Matchers.*;

public class ApiTest {

    @Test
    public void testPingEndpoint() {
        given()
            .when()
                .get("https://api.exemplo.com/ping")
            .then()
                .statusCode(200)
                .body("message", equalTo("pong"));
    }
}


  ```

   📌 3. Executando os Testes   <br>
🔹Se estiver usando Maven, execute: <br>
   
  ```
mvn test
  ```
🔹Se estiver usando Gradle, execute:
    
  ```
gradle test
  ```
🔹Se o teste for bem-sucedido, você verá uma saída semelhante a:
 ```
Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
  ```
    
    ` `
  
    ` `
📌 4. Testando um Endpoint com Autenticação
Se o endpoint exigir autenticação, podemos passar um token Bearer ou autenticação básica:

 ```
@Test
public void testComAutenticacao() {
    given()
        .auth()
        .preemptive()
        .basic("usuario", "senha")
    .when()
        .get("https://api.exemplo.com/secure-data")
    .then()
        .statusCode(200);
}

  ```
Para tokens JWT (Bearer Token):

 ```
@Test
public void testComBearerToken() {
    given()
        .header("Authorization", "Bearer seu_token_aqui")
    .when()
        .get("https://api.exemplo.com/protected")
    .then()
        .statusCode(200);
}

```
✅ Testando um Endpoint POST
Esse teste verifica se um novo usuário pode ser criado enviando um JSON no corpo da requisição.

  ```
import io.restassured.RestAssured;
import org.junit.jupiter.api.Test;
import static io.restassured.RestAssured.*;
import static org.hamcrest.Matchers.*;

public class ApiTest {

    @Test
    public void testCriarUsuario() {
        given()
            .header("Content-Type", "application/json")
            .body("{ \"nome\": \"João\", \"email\": \"joao@email.com\" }")
        .when()
            .post("https://api.exemplo.com/usuarios")
        .then()
            .statusCode(201)
            .body("message", equalTo("Usuário criado com sucesso"));
    }
}

```

✅ Explicação: <br>

* O given() define o corpo da requisição com JSON. <br>
* O post() envia os dados para a API. <br>
* O then() valida que o status da resposta é 201 (Created) e o corpo contém a mensagem esperada. <br>


  🛠 Testando um Endpoint PUT (Atualizar um Usuário)
Esse teste verifica se conseguimos atualizar os dados de um usuário existente.

```
  @Test
public void testAtualizarUsuario() {
    given()
        .header("Content-Type", "application/json")
        .body("{ \"nome\": \"João Silva\", \"email\": \"joaosilva@email.com\" }")
    .when()
        .put("https://api.exemplo.com/usuarios/1")
    .then()
        .statusCode(200)
        .body("message", equalTo("Usuário atualizado com sucesso"));
}

  ```
✅ Explicação:

* Usamos PUT para atualizar o usuário com ID 1.
* O JSON contém os novos dados do usuário.
* Verificamos que o status HTTP retornado é 200 (OK).


❌ Testando um Endpoint DELETE (Excluir um Usuário)
Aqui testamos se conseguimos excluir um usuário pelo ID.
  ```
@Test
public void testDeletarUsuario() {
    when()
        .delete("https://api.exemplo.com/usuarios/1")
    .then()
        .statusCode(204);
}

```
✅ Explicação:

* DELETE remove o usuário com ID 1.
* O status esperado é 204 (No Content), indicando que o usuário foi removido sem erro.


🔐 Testando um Endpoint Protegido com Token JWT (Autenticação Bearer)
Se a API exigir um token JWT para acessar os recursos, podemos passar o token no cabeçalho:
  ```
@Test
public void testComAutenticacaoJWT() {
    given()
        .header("Authorization", "Bearer seu_token_aqui")
    .when()
        .get("https://api.exemplo.com/dados-seguros")
    .then()
        .statusCode(200)
        .body("status", equalTo("Acesso permitido"));
}

```

✅ Explicação:

O cabeçalho "Authorization" recebe um token Bearer para autenticação.
A API deve retornar um status 200 (OK) se o token for válido.

🔄 Executando os Testes
Para rodar os testes, use:
  ```
mvn test  # Para Maven
gradle test  # Para Gradle
```
🎯 Conclusão
O REST-Assured facilita bastante os testes de APIs em Java, permitindo verificar status, corpo de resposta e autenticação de forma simples. Ele é ideal para integrar em pipelines CI/CD para garantir que os serviços REST estejam sempre funcionando corretamente.

Se precisar de mais exemplos, como testes com POST, PUT e DELETE, posso te ajudar a expandir! 🚀

📌 Para mais detalhes, consulte a [documentação oficial.](https://rest-assured.io/)
Agora, após executar os testes, o relatório estará disponível na pasta output.

# 📁 Abaixo está projetos que fiz com Rest-assured onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - Rest-assured](https://github.com/heyMichaelS/rest-assured-api)

<hr>
</details>

  
<details>
<summary>Supertest</summary>
 
  <br>
  
🚀 SuperTest - Testes de API Simples e Eficientes
O SuperTest é uma biblioteca para testes de API em Node.js, projetada para facilitar a verificação de endpoints REST e GraphQL. Ele se integra facilmente com frameworks como Express, Koa e outros, permitindo testar requisições HTTP de maneira simples e intuitiva.
  
  <br>
  
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

# 📁 Abaixo está projetos que fiz com Supertest onde coloquei em prática os ensinamentos de teste nesse framework.<br>

* [Projeto 1º - Superset](https://github.com/heyMichaelS/supertest_api)
<hr>
</details>
<br>
</details>


<details>
<summary>Automação Mobile</summary>
<br>

<details>
  <br>
  <summary>Maestro 📱</summary>
  
🔍 O que é o Maestro?
O Maestro é um framework de automação para testes de interface em aplicativos móveis, desenvolvido para ser mais simples e eficiente do que alternativas como o Appium. Ele permite a criação e execução de testes de forma rápida, utilizando uma sintaxe intuitiva baseada em YAML.

🛠️ Pré-requisitos
Antes de instalar o Maestro, certifique-se de que possui os seguintes requisitos:

✅ Java Development Kit (JDK) instalado e configurado no PATH do sistema <br>
✅ Ferramentas de linha de comando para iOS (Xcode CLI) para testes em dispositivos iOS  <br>
✅ Android SDK instalado e configurado para testes em Android  <br>


📌 Vantagens do Maestro sobre o Appium
<br>
    🔹 Mais simples e leve: Não depende de um servidor separado como o Appium <br>
    🔹 Configuração rápida: Exige menos dependências e é fácil de instalar <br>
    🔹 Sintaxe intuitiva: Testes escritos em YAML, sem necessidade de programação complexa <br>
    🔹 Execução eficiente: Testes são mais rápidos em comparação com o Appium <br>

🏗️ Estrutura de um Teste com Maestro
Os testes no Maestro são escritos em arquivos .yaml. Exemplo de um teste básico de login:

```
# login_test.yaml
appId: com.meuapp.mobile
---
- launchApp
- tapOn: "Login"
- insertText:
    text: "usuario@example.com"
    into: "Email"
- insertText:
    text: "senha123"
    into: "Senha"
- tapOn: "Entrar"
- assertVisible: "Dashboard"
```

Em meu repositório usei somente comandos windowns mas na documentação do maestro possoui as outras opções.

No windons é interessante instalar o comando do linux pode ajudar 

Instalação do WSL no Windows

1- Abrir o PowerShell como Administrador

* Pressione Win + X → Selecione Windows Terminal (Admin) ou PowerShell (Admin)
* Execute o comando:

```
wsl --install
```

* Isso instala o WSL com a distribuição padrão (Ubuntu).

2- Escolher outra distribuição Linux (Opcional)

* Para ver as distribuições disponíveis:

```
wsl --list --online
```

* Para instalar uma distribuição específica (exemplo: Debian):

```
wsl --install -d Debian
```
Verificar a Instalação

Execute:

```
wsl --list --verbose
```
* Se estiver rodando corretamente, aparecerá a distribuição instalada e seu estado.

5- Executar o Linux no Windowns

* Apenas digite wsl no terminal ou abra a distribuição Linux pelo menu Iniciar.


com WLS2 ativo e no terminal linux
Para baixar o maestro digite:

```
curl -fsSL "https://get.maestro.mobile.dev" | bash
```

No terminal do Windowns Powershell

```
adb -a -P 5037 nodaemon server
```
No terminal WSL2 Linux rode 

```
export ADB_SERVER_SOCKET=tcp:<IP>:5037
```
Verificar se adb esta conectado com device ira aparecer com comando:

```
adb devices
```
No Windowns possui umas diferenças para executar os tests no Maestro são as seguintes.


* DIgite no terminal do Windowns

```
ipconfig
```
* Anote o numero do IP 

Rodar um teste:

```
maestro --host <IP> test android-flow.yaml
```
Rodar testes em sub pastas:

```
maestro --host <IP> test ./subflows/sub.yaml
```
Para conseguir inspecionar os elementos do APP assim que rodar no Android Studio:

```
maestro --host <IP> studio
```

Conclusão
O Maestro é uma excelente alternativa ao Appium para automação de testes móveis, oferecendo um setup mais simples e uma execução mais rápida. Com integração facilitada em CI/CD e suporte a testes em dispositivos físicos e emuladores, é uma ferramenta poderosa para QA Mobile.

Se quiser explorar mais, consulte a [documentação oficial](https://docs.maestro.dev/)

# 📁 Abaixo está projetos que fiz com Maestro onde coloquei em prática os ensinamentos de teste mobile.<br>

* [Projeto 1º - Maestro](https://github.com/heyMichaelS/maestro)



  </details>
  <details>
<summary>Espresso</summary>
<br>

📱 Testes de UI Automatizados com Espresso - Android

Este documento apresenta um guia completo sobre Espresso, um framework de automação de testes para aplicações Android nativas. 
O Espresso permite validar a interface do usuário (UI) de forma rápida e eficiente, garantindo que a experiência do usuário seja consistente em diferentes cenários.

📌 1. O que é Espresso?
O Espresso faz parte da AndroidX Test Library e é desenvolvido pelo Google para facilitar a escrita de testes de interface gráfica (UI Tests). 
Ele permite que os testes interajam diretamente com os componentes do app, como botões, listas e campos de texto.

🚀 Vantagens do Espresso <br>
✅ Rápido e confiável (sincroniza automaticamente com a UI)  <br>
✅ Suporte nativo para JUnit e AndroidJUnitRunner  <br>
✅ Funciona em dispositivos reais e emuladores  <br>
✅ Suporte a testes de navegação, ações e validações  <br>

📌 2. Configuração do Ambiente  <br>
🔹 Pré-requisitos  <br>
✔ Android Studio instalado  <br>
✔ Dispositivo físico ou emulador configurado  <br>
✔ Gradle atualizado no projeto  <br>

🔹 Instalação do Espresso <br>
Adicione as seguintes dependências no build.gradle (Module: app):

```
dependencies {
    // Biblioteca principal do Espresso
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'

    // Extensão para testes com JUnit
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'

    // Runner para executar testes no Android
    androidTestImplementation 'androidx.test:runner:1.5.2'

    // Regras de teste para melhor controle do fluxo de execução
    androidTestImplementation 'androidx.test:rules:1.5.0'

    // Testes em RecyclerView
    androidTestImplementation 'androidx.test.espresso:espresso-contrib:3.5.1'
}

```

No build.gradle (Project: app), ative o runner de testes:

```
android {
    defaultConfig {
        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }
}

```

📌 3. Estrutura de um Teste com Espresso <br>
No Espresso, cada teste segue uma estrutura básica:  <br>
1️⃣ Localizar o elemento na tela  <br>
2️⃣ Executar uma ação (ex: clique, digitação)  <br>
3️⃣ Validar o resultado esperado  <br>

Exemplo de teste para verificar se um botão exibe um texto ao ser clicado:

```
@RunWith(AndroidJUnit4.class)
public class MainActivityTest {

    @Rule
    public ActivityScenarioRule<MainActivity> activityRule =
            new ActivityScenarioRule<>(MainActivity.class);

    @Test
    public void testButtonClick() {
        // Clicar no botão
        onView(withId(R.id.btn_click)).perform(click());

        // Verificar se o texto apareceu na tela
        onView(withId(R.id.txt_result)).check(matches(withText("Texto atualizado!")));
    }
}


```

📌 4. Principais Comandos do Espresso
🎯 Selecionando elementos

```
onView(withId(R.id.my_button)) // Seleciona por ID
onView(withText("Enviar"))      // Seleciona por texto
onView(withHint("Digite aqui")) // Seleciona por hint (placeholder)
onView(withContentDescription("Ícone")) // Seleciona por descrição de acessibilidade


```

✋ Interações

```
perform(click());         // Clique
perform(typeText("QA"));  // Digitar texto
perform(scrollTo());      // Rolar a tela até o elemento
perform(longClick());     // Clique longo
perform(swipeLeft());     // Deslizar para a esquerda

```
✅ Validações (Assertions)

```
check(matches(isDisplayed()));  // Verifica se o elemento está visível
check(matches(withText("OK"))); // Verifica se o texto está correto
check(matches(isChecked()));    // Verifica se um checkbox está marcado
check(doesNotExist());          // Verifica se um elemento NÃO existe

```

📌 5. Testando Listas (RecyclerView)
O Espresso possui suporte nativo para RecyclerView através da biblioteca espresso-contrib.

🔹 Teste de clique em um item da RecyclerView

```
onView(withId(R.id.recyclerView))
    .perform(RecyclerViewActions.actionOnItemAtPosition(2, click()));

```

🔹 Verificar se um item está visível na RecyclerView

```
onView(withRecyclerView(R.id.recyclerView)
        .atPositionOnView(0, R.id.item_text))
    .check(matches(withText("Primeiro item")));

```

📌 6. Testes com Activity Navigation
O Espresso permite testar a navegação entre telas, garantindo que os botões de transição funcionem corretamente.

```
@Test
public void testNavigationToSecondActivity() {
    // Clica no botão que leva para a segunda tela
    onView(withId(R.id.btn_navigate)).perform(click());

    // Verifica se a segunda tela foi aberta
    onView(withId(R.id.second_activity_layout)).check(matches(isDisplayed()));
}



```

📌 7. Execução dos Testes
Os testes podem ser executados de diferentes formas:

🔹 Via Android Studio <br>
1️⃣ Vá até Run > Run ‘Tests in package’   <br>
2️⃣ Escolha um dispositivo/emulador e execute  <br>

🔹 Via Terminal (Gradle)  <br>

```
./gradlew connectedAndroidTest


```

🔹 Via Comando ADB

```
adb shell am instrument -w -r -e class com.example.MyTest androidx.test.runner.AndroidJUnitRunner

```

📌 8. Melhores Práticas no Espresso
<br>
✔ Use Idling Resources para testes assíncronos (espera automática por carregamentos) <br>
✔ Evite sleep() e prefira IdlingResource ou waitForView() <br>
✔ Organize os testes usando Page Object Pattern <br>
✔ Use Regras de Teste (@Rule) para iniciar atividades automaticamente <br>
✔ Rodar testes em diferentes dispositivos para evitar dependência de layout específico <br>

📌 9. Exemplo de Estrutura de Pastas para Testes Espresso

```
📂 app/src/androidTest/java/com/example/myapp
 ├── 📂 ui_tests
 │    ├── MainActivityTest.java
 │    ├── LoginActivityTest.java
 │    ├── RecyclerViewTest.java
 ├── 📂 utils
 │    ├── CustomMatchers.java
 │    ├── TestUtils.java

```

📌 10. Conclusão
O Espresso é uma ferramenta poderosa para testes de UI no Android, garantindo qualidade e consistência na interface do usuário. 
Com uma abordagem bem estruturada e seguindo as melhores práticas, é possível criar testes robustos e confiáveis para qualquer aplicação Android.

Para mais informações veja na [documentação](https://developer.android.com/training/testing/espresso/basics?hl=pt-br)

</details>
</details>

<details>
<summary>Performance-tests</summary>
<br>

<details>
  <summary>Postman</summary>

  <br>
  
Postman para Testes de Performance 🚀
O Postman é uma ferramenta poderosa para testar APIs RESTful, mas além dos testes funcionais, ele também pode ser usado para testes de performance. Com o Runner do Postman e scripts no Pre-request Script e Tests, conseguimos simular diferentes cenários de carga.

Tipos de Testes de Performance no Postman <br>
🔹 Fixed Load – Simula um número fixo de requisições ao longo do tempo. <br>
🔹 Ramp-Up – Aumenta gradualmente a carga para analisar o comportamento do sistema sob pressão progressiva. <br>
🔹 Spike Test – Simula um pico repentino de requisições para avaliar a resiliência da API. <br>
🔹 Peak Test – Mede o desempenho sob carga máxima sustentada, verificando como o sistema lida com tráfego intenso. <br>

1️⃣ Instalar o Postman
  Baixe e instale o Postman pelo site oficial: [aqui](https://www.postman.com/downloads/)
  <br>
  
<p align="center">Com as collections configuradas só clicar nos tres ... e como na imagem abaixo clicar em Run Collection 
<p align="center"><img src="https://github.com/heyMichaelS/postman/blob/master/imagens/Run%20collection.png" alt="Sua Foto" width="350" height="500"/>

<p align="center">Após isso ira abrir as requisições que deseja testar marque somente a que vai fazer o teste de carga 
<p align="center">🔹Load Profile 🔹 Virtual Users 🔹Test Duration 
<p align="center"><img src="https://github.com/heyMichaelS/postman/blob/master/imagens/caminho%20performace.png " alt="Sua Foto" width="750" height="500"/>

# Abaixo está alguns exemplos que usei em uma API no wiremock

<p align="center"><img src="https://github.com/heyMichaelS/postman/blob/master/imagens/Teste%20Fixed.png" alt="Sua Foto" width="750" height="500"/>
<p align="center"> FIXED

<hr>
<p align="center"><img src="https://github.com/heyMichaelS/postman/blob/master/imagens/Rump%20up%20no%20postman.png"  alt="Sua Foto" width="750" height="500"/>
<p align="center"> RAMP UP
<hr>
  
<p align="center"><img src= "https://github.com/heyMichaelS/postman/blob/master/imagens/Teste%20Peak.png"  alt="Sua Foto" width="750" height="500"/>
<p align="center"> PEAK
  <hr>
<p align="center"><img src= "https://github.com/heyMichaelS/postman/blob/master/imagens/Teste%20Spike.png"  alt="Sua Foto" width="750" height="500"/>
  <p align="center"> SPIKE
  <hr>
<p align="center"><img src= "https://github.com/heyMichaelS/postman/blob/master/imagens/Teste%20Ramp%20up%20(erro%20500).png"  alt="Sua Foto" width="750" height="500"/>
 <p align="center"> RAMP UP (GET COM ERRO 500)
  </details>

<details>
  <summary>JMeter</summary>
  
<br>
  
Apache JMeter - Testes de Performance

🔍 O que é o Apache JMeter?

<br>

O Apache JMeter é uma ferramenta open-source desenvolvida pela Apache Software Foundation para realizar testes de carga e performance em aplicações web, APIs, bancos de dados e muito mais. Ele permite simular múltiplos usuários simultâneos e analisar o desempenho do sistema sob diferentes condições.

Principais características do JMeter:  <br>

<br>

✅ Testes de carga, stress, e desempenho para aplicações web e APIs <br>
✅ Simulação de múltiplos usuários simultâneos  <br>
✅ Suporte a protocolos como HTTP, HTTPS, FTP, JDBC, JMS, entre outros  <br>
✅ Relatórios detalhados com métricas de resposta, tempo de execução, erro, etc.  <br>
✅ Extensível através de plugins personalizados  <br>


🛠 Pré-requisitos
Antes de instalar o JMeter, certifique-se de que você possui os seguintes requisitos no seu sistema:

Java JDK 8 ou superior → Você pode verificar sua versão com:

```
java -version
```
Se não estiver instalado, faça o download [aqui.](https://www.oracle.com/java/technologies/downloads/#java11?er=221886) <br>
JMeter → Baixe a versão mais recente [aqui.](https://jmeter.apache.org/download_jmeter.cgi) <br>

🚀 Instalação e Configuração <br>
1️⃣ Baixe o Apache JMeter e extraia o conteúdo do arquivo ZIP para um local no seu computador. <br>
2️⃣ Abra o JMeter: <br>

No Windows: execute o arquivo jmeter.bat dentro da pasta bin/. <br>

3️⃣ Verifique se o JMeter abriu corretamente. Você verá a interface gráfica do JMeter pronta para criar testes de carga. <br>

🎯 Criando um Teste no JMeter <br>
Agora vamos criar um teste de carga básico. <br>

1️⃣ Adicionando um Grupo de Threads (Usuários Virtuais): <br>

Clique com o botão direito em "Test Plan" → Add → Threads (Users) → Thread Group <br>

<br>

Configure os parâmetros básicos:
Number of Threads (Users): Quantidade de usuários simultâneos
Ramp-Up Period (seconds): Tempo para atingir o número total de usuários
Loop Count: Quantidade de repetições do teste

2️⃣ Adicionando uma Requisição HTTP: <br>

Clique com o botão direito no "Thread Group" → Add → Sampler → HTTP Request 

<p align="center"><img src=https://github.com/heyMichaelS/JMeter/blob/master/imagens/Captura%20de%20tela%202025-02-28%20025642.png  alt="Sua Foto" width="800" height="500"/>


<br>

Configure os seguintes campos:
Server Name or IP: Digite a URL do servidor (exemplo: meusite.com)
Method: Escolha GET, POST, PUT, DELETE
Path: Insira o endpoint da API (/api/login, /api/produtos)
Parâmetros: Vá até a aba "Parameters" e adicione os parâmetros da requisição

<br>

3️⃣ Adicionando Headers HTTP (Opcional):

Botão direito no "Thread Group" → Add → Config Element → HTTP Header Manager <br>
Clique em Add e insira os headers necessários, como: <br>

<p align="center"><img src=https://github.com/heyMichaelS/JMeter/blob/master/imagens/Captura%20de%20tela%202025-02-28%20025629.png alt="Sua Foto" width="800" height="500"/>

```
Name: Accept
Value: */*
```

Exemplo:
```
Key: Authorization  
Value: Bearer meu_token_de_autenticacao
```

<br>

4️⃣ Adicionando um Listener para visualizar os resultados:

Botão direito no "Thread Group" → Add → Listener → View Results Tree <br>

📌 Executando e Analisando os Resultados
<br>
1️⃣ Clique no botão "Start" (▶️) para iniciar o teste <br>
2️⃣ Vá até o "View Results Tree" para visualizar as respostas das requisições <br>
3️⃣ Analise os tempos de resposta, erros e status HTTP retornados <br>

🔌 Instalando Plugins no JMeter
Para obter mais funcionalidades, instale o JMeter Plugins Manager:

1️⃣ Baixe o Plugin Manager: Baixar Plugin Manager  <br>
2️⃣ Copie o arquivo JMeterPlugins-Manager.jar para a pasta:  <br>

```
apache-jmeter-5.x/lib/ext/
```

3️⃣ Abra o JMeter e vá até:  <br>

Options → Plugin Manager  <br>

4️⃣ Instale o plugin jp@gc - Ultimate Thread Group, que permite configurações mais avançadas de carga.  <br>

📊 Gerando Relatórios de Teste

<br>

Após a execução do teste, você pode gerar um relatório HTML detalhado com gráficos e estatísticas.

1️⃣ Configurar a geração do relatório: <br>

* Criar uma pasta para armazenar os logs (D:/apache-jmeter/logs/) <br>
* Criar um arquivo para o log do teste (log.jtl) <br>

2️⃣ Executar o teste e salvar os resultados: <br>

```
jmeter -n -t teste.jmx -l D:/apache-jmeter/logs/log.jtl -e -o D:/apache-jmeter/reports/
```

3️⃣ O relatório será gerado na pasta especificada e pode ser acessado via navegador.  <br>

<p align="center"><img src=https://github.com/heyMichaelS/JMeter/blob/master/imagens/Captura%20de%20tela%202025-02-28%20031539.png  alt="Sua Foto" width="700" height="400"/>


🚀 Conclusão
O Apache JMeter é uma ferramenta poderosa para testes de carga e desempenho, permitindo simular múltiplos usuários simultâneos e analisar métricas importantes do sistema.

Seja testando APIs, aplicações web, microsserviços ou bancos de dados, o JMeter pode ser configurado para fornecer relatórios detalhados e ajudar na identificação de gargalos de desempenho.


<hr>
  </details>

<details>
<summary>k6</summary>
<br>
  
📌 k6 - Testes de Carga e Performance
O k6 é uma ferramenta de código aberto para testes de carga e desempenho. Ele permite simular usuários simultâneos acessando uma aplicação para verificar seu comportamento sob diferentes níveis de carga.

Desenvolvido em JavaScript, o k6 é leve, eficiente e projetado para testes em CI/CD e ambientes escaláveis.

🔹 Site oficial: [https://k6.io/](https://k6.io/) <br>
🔹 Repositório GitHub: [https://github.com/grafana/k6](https://github.com/grafana/k6) <br>


🛠️ Pré-requisitos  <br>
Antes de instalar o k6, verifique se seu ambiente atende aos seguintes requisitos:  <br>

✔ Node.js (se for usar scripts avançados com módulos)  <br>
✔ Sistema Operacional: Windows, macOS ou Linux  <br>
✔ Git (opcional, para gerenciar repositórios com testes) <br>

📌 Instalação  <br>
🔹 Windows  <br>
1️⃣ Baixe o binário oficial no [site do k6](https://k6.io/open-source/) <br>
2️⃣ Extraia o arquivo e adicione ao Path do Windows <br>
3️⃣ Teste a instalação com o comando: <br>


```
k6 version
```

🚀 Criando um Teste de Carga Simples
Crie um arquivo teste.js e adicione o seguinte código:

```
import http from 'k6/http';
import { sleep, check } from 'k6';

export let options = {
    vus: 10, // Número de usuários virtuais simultâneos
    duration: '10s', // Tempo total do teste
};

export default function () {
    let res = http.get('https://test-api.k6.io');
    
    // Validações básicas
    check(res, {
        'status é 200': (r) => r.status === 200,
        'tempo de resposta menor que 500ms': (r) => r.timings.duration < 500,
    });

    sleep(1); // Simula um tempo de espera entre as requisições
}
```
📌 Rodando o Teste
```
k6 run teste.js
```
A saída exibirá estatísticas detalhadas sobre a performance da API testada.


📊 Testes com Diferentes Cenários de Carga <br>
🔹 Teste de Pico de Usuários <br>
```
export let options = {
    stages: [
        { duration: '10s', target: 20 }, // Aumenta para 20 usuários em 10s
        { duration: '30s', target: 50 }, // Mantém 50 usuários por 30s
        { duration: '10s', target: 0 },  // Reduz para 0 usuários em 10s
    ],
};
```
🔹 Teste de Estresse
```
export let options = {
    vus: 100,
    duration: '1m',
};
```
🔹 Teste de Spike (pico repentino)

```
export let options = {
    stages: [
        { duration: '5s', target: 100 },
        { duration: '10s', target: 500 },
        { duration: '5s', target: 100 },
    ],
};

```
📌 Integração com CI/CD
O k6 pode ser facilmente integrado a GitHub Actions, Jenkins, GitLab CI e outras ferramentas.

Exemplo de execução automática no GitHub Actions:

```
name: Teste de Performance

on: [push]

jobs:
  k6-test:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout do repositório
        uses: actions/checkout@v2

      - name: Instalar k6
        run: sudo apt install k6

      - name: Executar testes de carga
        run: k6 run teste.js

```

📊 Tipos de Testes de Carga e seus Cenários <br>
1️⃣ Teste de Carga Padrão (Simula tráfego normal)  <br>
📌 Objetivo: Avaliar o desempenho da aplicação sob carga normal esperada.  <br>
📌 Como funciona: Mantém um número fixo de usuários enviando requisições por um período.  <br>

```
export let options = {
    vus: 50, // Número fixo de usuários virtuais
    duration: '1m', // Executa o teste por 1 minuto
};
```
✅ Útil para verificar uso regular da aplicação.  <br>

2️⃣ Teste de Stress (Descobrir o limite da aplicação)  <br>
📌 Objetivo: Testar a aplicação sob carga extrema para identificar seu limite.  <br>
📌 Como funciona: Aumenta progressivamente o número de usuários até o sistema começar a falhar.  <br>
```
export let options = {
    stages: [
        { duration: '30s', target: 100 },  // Aumenta para 100 usuários em 30s
        { duration: '1m', target: 500 },   // Mantém 500 usuários por 1 minuto
        { duration: '30s', target: 0 },    // Reduz gradualmente para 0
    ],
};

```
✅ Indica ponto de falha e possíveis gargalos da aplicação.  <br>


3️⃣ Teste de Pico (Spike Test)  <br>
📌 Objetivo: Avaliar como a aplicação lida com um aumento repentino e curto de tráfego.  <br>
📌 Como funciona: Simula um pico rápido de usuários que logo desaparece.  <br>

```
export let options = {
    stages: [
        { duration: '5s', target: 200 },  // Sobe rapidamente para 200 usuários
        { duration: '10s', target: 200 }, // Mantém por 10s
        { duration: '5s', target: 0 },    // Cai rapidamente para 0
    ],
};

```
✅ Testa a resiliência e recuperação do sistema após uma alta repentina de tráfego.  <br>


4️⃣ Teste de Soak (Teste de Resistência)  <br>
📌 Objetivo: Avaliar a estabilidade da aplicação sob uma carga contínua por um longo período.  <br>
📌 Como funciona: Mantém um número fixo de usuários por um longo tempo para identificar vazamentos de memória ou degradação de performance.  <br>
```
export let options = {
    vus: 50, // Número de usuários constantes
    duration: '30m', // Executa por 30 minutos
};

```
✅ Indicado para verificar vazamento de memória e degradação ao longo do tempo.  <br>



5️⃣ Teste de Escalabilidade (Ramp Up / Ramp Down)  <br>
📌 Objetivo: Avaliar como a aplicação responde a aumentos e reduções graduais de tráfego.  <br>
📌 Como funciona: Aumenta e reduz progressivamente os usuários.  <br>

```
export let options = {
    stages: [
        { duration: '1m', target: 50 },   // Começa com 50 usuários
        { duration: '2m', target: 200 },  // Aumenta para 200 usuários
        { duration: '2m', target: 500 },  // Sobe para 500 usuários
        { duration: '2m', target: 200 },  // Reduz para 200 usuários
        { duration: '1m', target: 50 },   // Volta para 50 usuários
    ],
};

```
✅ Bom para verificar como a aplicação escala dinamicamente.  <br>

6️⃣ Teste de Picos Periódicos (Burst Test)  <br>
📌 Objetivo: Testar como o sistema reage a picos intermitentes de carga.  <br>
📌 Como funciona: Simula picos repetidos de tráfego com momentos de descanso entre eles.  <br>

```
export let options = {
    stages: [
        { duration: '10s', target: 100 },  // Pico para 100 usuários
        { duration: '20s', target: 10 },   // Volta para 10 usuários
        { duration: '10s', target: 150 },  // Pico para 150 usuários
        { duration: '20s', target: 10 },   // Volta para 10 usuários
        { duration: '10s', target: 200 },  // Pico para 200 usuários
    ],
};
```
✅ Indicado para sistemas que enfrentam tráfego intermitente, como e-commerce em promoções.

## Teste específicos exemplos

📌 Cenários de Teste de Carga Específicos
1️⃣ Teste de Checkout (E-commerce)
📌 Objetivo: Avaliar o desempenho do fluxo de checkout em uma loja virtual sob alta demanda.
📌 Cenário: Simula usuários navegando pelo site, adicionando produtos ao carrinho e finalizando a compra.

<br>

```
import http from 'k6/http';
import { sleep } from 'k6';

export let options = {
    stages: [
        { duration: '30s', target: 50 },   // 50 usuários navegando no site
        { duration: '1m', target: 200 },   // Aumenta para 200 usuários comprando
        { duration: '30s', target: 50 },   // Reduz novamente para 50
    ],
};

export default function () {
    http.get('https://loja-teste.com/produtos');
    sleep(1);
    http.post('https://loja-teste.com/carrinho', { id: 123, quantidade: 1 });
    sleep(1);
    http.post('https://loja-teste.com/checkout', { pagamento: 'cartão' });
}
```
✅ Útil para testar blackfriday, promoções ou eventos com alta demanda.


2️⃣ Teste de Login Massivo (Aplicação Web)
📌 Objetivo: Simular milhares de usuários tentando fazer login ao mesmo tempo.
📌 Cenário: Simula múltiplos usuários acessando a plataforma e autenticando.
```
import http from 'k6/http';
import { sleep } from 'k6';

export let options = {
    stages: [
        { duration: '1m', target: 1000 },  // 1000 logins simultâneos
        { duration: '2m', target: 3000 },  // Aumenta para 3000 usuários
        { duration: '1m', target: 0 },     // Finaliza os testes
    ],
};

export default function () {
    let res = http.post('https://app-teste.com/login', JSON.stringify({
        email: `user${__VU}@teste.com`, 
        password: '123456'
    }), { headers: { 'Content-Type': 'application/json' } });

    sleep(1);
}
```
✅ Ótimo para testar autenticação e performance do banco de dados em grande escala.


3️⃣ Teste de API com Alta Concorrência
📌 Objetivo: Testar se uma API aguenta um alto volume de requisições simultâneas.
📌 Cenário: Simula múltiplas requisições GET e POST para uma API RESTful.

```
import http from 'k6/http';
import { sleep } from 'k6';

export let options = {
    vus: 500,    // 500 usuários simultâneos
    duration: '2m', // Executa o teste por 2 minutos
};

export default function () {
    http.get('https://api.meusistema.com/dados');
    sleep(0.5);
    http.post('https://api.meusistema.com/enviar', JSON.stringify({ nome: 'QA Test' }), {
        headers: { 'Content-Type': 'application/json' }
    });
}
```
✅ Bom para testar tempo de resposta da API e possíveis gargalos.

4️⃣ Teste de Microservices (Comunicação entre serviços)
📌 Objetivo: Avaliar a comunicação entre microsserviços sob carga.
📌 Cenário: Simula chamadas entre múltiplas APIs.
```
import http from 'k6/http';
import { check, sleep } from 'k6';

export let options = {
    vus: 300,
    duration: '3m',
};

export default function () {
    let auth = http.post('https://auth.meusistema.com/login', JSON.stringify({
        usuario: 'admin', senha: 'teste123'
    }), { headers: { 'Content-Type': 'application/json' } });

    check(auth, { "Login bem-sucedido": (res) => res.status === 200 });

    let response = http.get('https://dados.meusistema.com/info', {
        headers: { 'Authorization': `Bearer ${auth.json().token}` }
    });

    check(response, { "API de dados respondeu": (res) => res.status === 200 });

    sleep(1);
}


```
✅ Ajuda a identificar problemas de autenticação e integração entre serviços.

5️⃣ Teste de Tempo de Sessão (Simulação de Usuários Reais)
📌 Objetivo: Simular usuários navegando por longos períodos na aplicação.
📌 Cenário: Usuários entram no sistema e realizam interações por um tempo específico.
```
import http from 'k6/http';
import { sleep } from 'k6';

export let options = {
    vus: 100,
    duration: '1h',
};

export default function () {
    http.get('https://sistema.com/dashboard');
    sleep(3);
    http.get('https://sistema.com/perfil');
    sleep(3);
    http.get('https://sistema.com/configuracoes');
    sleep(3);
}
```
✅ Testa estabilidade e vazamento de memória em longas sessões de uso.

6️⃣ Teste de Banco de Dados (Alta Taxa de Queries)
📌 Objetivo: Simular altos volumes de queries sendo executadas ao mesmo tempo.
📌 Cenário: Usuários acessando e enviando consultas ao banco de dados.
```
import http from 'k6/http';
import { sleep } from 'k6';

export let options = {
    vus: 200,
    duration: '5m',
};

export default function () {
    http.get('https://api.sistema.com/relatorios');
    sleep(0.5);
    http.get('https://api.sistema.com/usuarios');
    sleep(0.5);
    http.post('https://api.sistema.com/inserir', JSON.stringify({
        nome: 'Teste', email: 'teste@qa.com'
    }), { headers: { 'Content-Type': 'application/json' } });
}
```
✅ Ajuda a medir o impacto de consultas concorrentes no banco de dados.

🚀 Como Executar os Testes?
Após salvar o código em um arquivo teste.js, execute com:

```
k6 run teste.js
```

🔚 Conclusão
O k6 é uma ferramenta poderosa para garantir que sistemas suportem grandes volumes de usuários sem degradação. Ele pode ser integrado com CI/CD, possui suporte a múltiplos cenários de teste e é extremamente eficiente.

Se quiser explorar mais, consulte a [documentação oficial:](https://grafana.com/docs/k6/latest/)

# 📁 Abaixo está projetos que fiz com K6 onde coloquei em prática os ensinamentos de teste carga.<br>

* [Projeto 1º - K6](https://github.com/heyMichaelS/K6)

<hr>

</details>
<details>
<summary>Wiremock</summary>
  <br>
📌 WireMock - Introdução
O WireMock é uma ferramenta de mocking de APIs que permite simular servidores HTTP para testes. Com ele, você pode criar respostas pré-definidas para chamadas HTTP sem depender de um servidor real. Isso é útil para testar sistemas que interagem com APIs de terceiros ou quando a API ainda não está desenvolvida.
 
  <br>
  
🚀 Principais Vantagens do WireMock 
  
  <br>

✅ Simula APIs HTTP – Permite criar respostas personalizadas para diferentes requisições <br>
✅ Testes isolados – Evita dependência de serviços externos, garantindo estabilidade nos testes <br>
✅ Suporte a JSON e XML – Facilita a criação de mocks com diferentes formatos de dados <br>
✅ Grava e reproduz chamadas HTTP – Permite capturar requisições reais para testes posteriores  <br>
✅ Integração com frameworks de teste – Pode ser usado com JUnit, REST-Assured e outras ferramentas <br>

🛠 Passo a Passo: Instalando e Configurando o WireMock
  
  <br>
  
  <br>
  
📌 1. Pré-requisitos <br>
<br> ✔ Java JDK 8 ou superior instalado  
<br> ✔ Maven ou Gradle para gerenciamento de dependências 

Para verificar a versão do Java:

```
java -version
```
Caso não tenha, baixe o JDK em:([https://jdk.java.net/](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html))

📌 2. Instalando o WireMock <br>

🔹 Opção 1: Usando o Standalone JAR <br>

Baixe o WireMock standalone JAR: <br>

```
wget https://repo1.maven.org/maven2/com/github/tomakehurst/wiremock-standalone/3.3.1/wiremock-standalone-3.3.1.jar
```
Depois, inicie o WireMock localmente:

```
java -jar wiremock-standalone-3.3.1.jar
```
Isso iniciará o servidor WireMock na porta 8080 por padrão.

🔹 Opção 2: Usando Maven
Adicione esta dependência ao seu pom.xml:

```
<dependency>
    <groupId>com.github.tomakehurst</groupId>
    <artifactId>wiremock-jre8</artifactId>
    <version>3.3.1</version>
</dependency>
```
🔹 Opção 3: Usando Gradle
Adicione no build.gradle:

```
dependencies {
    testImplementation 'com.github.tomakehurst:wiremock-jre8:3.3.1'
}
```

📌 3. Criando um Mock de API
Agora, vamos configurar um endpoint falso que retorna um JSON.

🔹 Criando um Stub de Requisição GET

```
curl -X POST http://localhost:8080/__admin/mappings \
     -H "Content-Type: application/json" \
     -d '{
          "request": {
              "method": "GET",
              "url": "/api/usuarios"
          },
          "response": {
              "status": 200,
              "body": "[{\"id\":1, \"nome\":\"João\"}, {\"id\":2, \"nome\":\"Maria\"}]",
              "headers": {
                  "Content-Type": "application/json"
              }
          }
      }'
```
📌 Explicação:

* Sempre que alguém acessar http://localhost:8080/api/usuarios, o WireMock responderá com um JSON simulando usuários.
* O status da resposta será 200 (OK).

📌 4. Testando o Mock com REST-Assured
Podemos testar essa API mockada com REST-Assured:
```
import static io.restassured.RestAssured.*;
import static org.hamcrest.Matchers.*;
import org.junit.jupiter.api.Test;

public class WireMockTest {
    @Test
    public void testMockUsuarios() {
        given()
        .when()
            .get("http://localhost:8080/api/usuarios")
        .then()
            .statusCode(200)
            .body("[0].nome", equalTo("João"));
    }
}
```
✅ Esse teste valida que a API mockada está retornando o JSON corretamente.

📌 5. Rodando os Testes
Se estiver usando Maven:
```
mvn test
```
Se estiver usando Gradle:
```
gradle test
```

🎯 Conclusão
O WireMock é uma ferramenta poderosa para criar mocks de APIs de forma rápida e eficiente. Ele permite testar aplicações desacopladas de serviços externos e garante estabilidade nos testes.



<br> ✔ Simula APIs HTTP sem depender de servidores reais 
<br> ✔ Funciona com JUnit, REST-Assured, Selenium e Cypress 
<br> ✔ Útil para testes de contrato e integração 

Se precisar de mais exemplos ou integração com CI/CD

# 📁 Abaixo está projetos que fiz com Wiremock onde coloquei em prática os ensinamentos .<br>

* [Projeto 1º - Wiremock](https://github.com/heyMichaelS/wiremock)



<hr>
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
