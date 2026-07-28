#  Casos de testes manuais e reportes (BDD / Gherkin)

##  Sobre o Projeto

Este repositório contém a especificação e documentação de cenários de teste de **Garantia de Qualidade (QA)** focados em fluxos de regressão e testes ponta a ponta (E2E). O objetivo é validar funcionalidades críticas como **Autenticação, Usabilidade, Busca e Filtros** em 4 ecossistemas digitais.

---

##  Estrutura da Suíte de Testes

* **Módulo 1:** LinkedIn - *Rede Profissional*
* **Módulo 2:** Magazine Luiza - *E-commerce Retail*
* **Módulo 3:** Mercado Livre - *Marketplace & Filtros*
* **Módulo 4:** Amazon Brasil - *Interface & Navegação*

---

## Tabela de Evidências Manuais

## 📸 Tabela de Evidências Manuais - LinkedIn

| Módulo | Cenário / Tag | Descrição do Cenário | Status | Evidência Visual |
| :--- | :--- | :--- | :---: | :---: |
| **LinkedIn** | @CT01_LI | Acessar página de criar conta | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/891f8a1e-5292-4784-9393-39065f5c9220) |
| **LinkedIn** | @CT02_LI | E-mail com formato inválido | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/18f7c1c7-f04a-4e7c-91e2-8956a049a05e) |
| **LinkedIn** | @CT03_LI | Login com campo de e-mail vazio | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/28bb1924-644a-4791-be95-c6b95d052204) |
| **LinkedIn** | @CT04_LI | Login com campo de senha vazia | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/f59912e5-8d44-47f4-afd9-cce45801d703) |
| **LinkedIn** | @CT05_LI | Validação de senha curta/sem número | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/99b44779-1342-441e-b183-de434e2f4396) |
| **LinkedIn** | @CT06_LI | Comportamento dos botões Continuar | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/9073ea9d-99bb-4010-853f-dcb6cbc316af) |

## 📸 Tabela de Evidências Manuais - Magazine Luiza

| Módulo | Cenário / Tag | Descrição do Cenário | Status | Evidência Visual |
| :--- | :--- | :--- | :---: | :---: |
| **Magazine Luiza** | @CT01_LUISA | E-mail correto com senha incorreta | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/aa171546-c4b3-49d3-8676-889264f0f6fc) |
| **Magazine Luiza** | @CT02_LUISA | E-mail sem "@" com senha correta | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/b94329c6-ac35-47f9-8566-5719c46909b2) |
| **Magazine Luiza** | @CT03_LUISA | E-mail correto com campo de senha vazio | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/2c661245-4873-40c1-bf03-63a3bef41d79) |
| **Magazine Luiza** | @CT04_LUISA | Testar funcionalidade de mostrar/ocultar senha | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/b0c99483-0a77-43a4-a507-f4840b02e61e) |
| **Magazine Luiza** | @CT05_LUISA | Tentativa de avançar com e-mail em branco | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/7445702c-4d36-446d-b901-775f345a39b6) |
| **Magazine Luiza** | @CT06_LUISA | Validar limite mínimo de caracteres na senha | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/6d49f37e-313f-4c38-9aec-e2b7c7d5569a) |

# 🟡 03. Mercado Livre

### 📸 Tabela de Evidências Manuais (Mercado Livre)

| Módulo | Cenário / Tag | Descrição do Cenário | Status | Evidência Visual |
| :--- | :--- | :--- | :---: | :---: |
| **Mercado Livre** | @CT01_ML | Autocompletar na busca por palavra-chave | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/31a9bd23-3269-46e3-acf6-5bb590da956b) |
| **Mercado Livre** | @CT02_ML | Busca geral com resultados válidos | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/18bd2501-1c56-4d6b-81de-15e3718f537e) |
| **Mercado Livre** | @CT03_ML | Busca por termo inexistente / sem resultados | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/d3eb82a5-e23c-48bd-b7a2-1cb5986c69c1) |
| **Mercado Livre** | @CT04_ML | Aplicar filtro de pesquisa por marca | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/9808ec6c-cd5d-475f-a72d-514f3d054578) |
| **Mercado Livre** | @CT05_ML | Aplicar filtro de faixa de preço | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/f18a77da-4853-4659-8880-e77bdf4be32d) |
| **Mercado Livre** | @CT06_ML | Ordenar resultados da busca por menor preço | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/f12cf35d-ff27-47d9-ab86-29dc2d5f0920) |

## 🟠 04. Amazon Brasil

### 📸 Tabela de Evidências Manuais (Amazon Brasil)

| Módulo | Cenário / Tag | Descrição do Cenário | Status | Evidência Visual |
| :--- | :--- | :--- | :---: | :---: |
| **Amazon** | @CT01_AZ | Validar a visibilidade da opção de login na barra superior | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/83080b59-d0c9-4702-b11b-8d57229adc01) |
| **Amazon** | @CT02_AZ | Verificar a presença e clareza da barra de busca principal | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/addc2dea-4263-43f3-b5e4-a2c7dd52a17b) |
| **Amazon** | @CT03_AZ | Expandir o menu lateral "Todos" para navegação por categorias | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/2e113cac-cbca-4026-84af-96905f3d02e7) |
| **Amazon** | @CT04_AZ | Navegação a partir de banners publicitários e carrossel | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/bc962a97-6b38-4d82-b3de-3c687c7d9d4e) |
| **Amazon** | @CT05_AZ | Validar consistência de layout, alinhamentos e contraste da Home | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/a9f202a8-2569-46cb-b960-156620f4d752) |
| **Amazon** | @CT06_AZ | Acionamento do menu suspenso em "Contas e Listas" via hover | 🟢 PASSED | [Ver Evidência](https://github.com/user-attachments/assets/33e813ef-34ca-4300-aeeb-2893ba714407) |

### 📑 Cenários de Teste & Evidências Visuais

#### 📌 **`@CT01_LI` - Acessar a página de criação de conta**
* **Dado** que o usuário está na página de login do LinkedIn
* **Quando** clica em "Cadastre-se agora"
* **Então** o sistema redireciona para a página de criação de conta

<details>
<summary>📸 <b>Ver evidência visual: Acessar página de criar conta</b></summary>
<br>
<img width="2560" height="998" alt="abrir criar conta" src="https://github.com/user-attachments/assets/891f8a1e-5292-4784-9393-39065f5c9220" />
</details>

<br>

#### 📌 **`@CT02_LI` - Tentativa de login com e-mail em formato inválido**
* **Dado** que o usuário insere um e-mail com formato inválido
* **Quando** tenta prosseguir com o login
* **Então** o sistema deve exibir uma mensagem de alerta de e-mail inválido

<details>
<summary>📸 <b>Ver evidência visual: E-mail com formato inválido</b></summary>
<br>
<img width="2560" height="982" alt="EMAIL COM FORMATO INVÁLIDO" src="https://github.com/user-attachments/assets/18f7c1c7-f04a-4e7c-91e2-8956a049a05e" />
</details>

<br>

#### 📌 **`@CT03_LI` - Login mantendo campo de e-mail vazio**
* **Dado** que o usuário não preenche o campo de e-mail
* **Quando** tenta prosseguir com a autenticação
* **Então** o sistema deve solicitar o preenchimento do campo de e-mail

<details>
<summary>📸 <b>Ver evidência visual: Login com campo de e-mail vazio</b></summary>
<br>
<img width="2560" height="994" alt="Login com campo de email vazio" src="https://github.com/user-attachments/assets/28bb1924-644a-4791-be95-c6b95d052204" />
</details>

<br>

#### 📌 **`@CT04_LI` - Login mantendo campo de senha vazio**
* **Dado** que o usuário preenche um e-mail válido
* **Mas** deixa o campo de senha em branco
* **Quando** tenta realizar o login
* **Então** o sistema exibe alerta informando a necessidade da senha

<details>
<summary>📸 <b>Ver evidência visual: Login com campo de senha vazio</b></summary>
<br>
<img width="2554" height="995" alt="login com campo de senha vazia" src="https://github.com/user-attachments/assets/f59912e5-8d44-47f4-afd9-cce45801d703" />
</details>

<br>

#### 📌 **`@CT05_LI` - Validação de senha abaixo do limite mínimo de caracteres**
* **Dado** que o usuário tenta cadastrar uma nova senha
* **Quando** insere uma senha curta e sem caracteres numéricos
* **Então** o sistema deve bloquear o avanço informando os requisitos de segurança

<details>
<summary>📸 <b>Ver evidência visual: Validação de senha curta</b></summary>
<br>
<img width="2558" height="990" alt="senha curta, sem numero" src="https://github.com/user-attachments/assets/99b44779-1342-441e-b183-de434e2f4396" />
</details>

<br>

#### 📌 **`@CT06_LI` - Verificar comportamento dos botões "Continuar"**
* **Dado** que o usuário navega pelo fluxo de autenticação
* **Quando** interage com os botões "Continuar"
* **Então** o sistema responde mantendo o estado correto das validações de tela

<details>
<summary>📸 <b>Ver evidência visual: Comportamento dos botões Continuar</b></summary>
<br>
<img width="2560" height="990" alt="Verificar comportamento dos botões “Continuar” 1" src="https://github.com/user-attachments/assets/9073ea9d-99bb-4010-853f-dcb6cbc316af" />
<br><br>
<img width="2588" height="359" alt="Verificar comportamento dos botões “Continuar” 2" src="https://github.com/user-attachments/assets/8c2009da-d8ec-4bcd-80af-8d39e507f5f2" />
</details>

---
---

#### 📌 **`@CT01_LUISA` - Tentativa de login com e-mail correto e senha incorreta**
* **Dado** que o usuário insere um e-mail válido no campo de autenticação
* **E** preenche o campo de senha com uma senha incorreta
* **Quando** clica em "Continuar"
* **Então** o sistema deve exibir uma mensagem de erro indicando dados inválidos

<details>
<summary>📸 <b>Ver evidência visual: E-mail correto e senha errada</b></summary>
<br>
<img width="2556" height="992" alt="EMAIL CORRERO COM SENHA ERRADA" src="https://github.com/user-attachments/assets/aa171546-c4b3-49d3-8676-889264f0f6fc" />
</details>

<br>

#### 📌 **`@CT02_LUISA` - Tentativa de login com e-mail sem o caractere "@"**
* **Dado** que o usuário insere um e-mail sem o formato válido (sem "@")
* **E** insere a senha correta
* **Quando** tenta prosseguir com o login
* **Então** o sistema deve alertar que o e-mail digitado é inválido

<details>
<summary>📸 <b>Ver evidência visual: E-mail sem '@'</b></summary>
<br>
<img width="2556" height="992" alt="email sem o arroba com senha correta" src="https://github.com/user-attachments/assets/b94329c6-ac35-47f9-8566-5719c46909b2" />
</details>

<br>

#### 📌 **`@CT03_LUISA` - Tentativa de login com e-mail correto e senha vazia**
* **Dado** que o usuário preenche um e-mail válido
* **Mas** deixa o campo de senha completamente em branco
* **Quando** tenta realizar a autenticação
* **Então** o sistema deve solicitar o preenchimento do campo de senha

<details>
<summary>📸 <b>Ver evidência visual: E-mail correto com campo de senha vazio</b></summary>
<br>
<img width="2547" height="893" alt="email correto com campo de senha vazio" src="https://github.com/user-attachments/assets/2c661245-4873-40c1-bf03-63a3bef41d79" />
</details>

<br>

#### 📌 **`@CT04_LUISA` - Alternar visualização da máscara do campo de senha**
* **Dado** que o usuário digitou uma senha no campo de texto
* **Quando** clica no ícone de "exibir/ocultar senha"
* **Então** o sistema deve alternar a visibilidade entre os caracteres e a máscara

<details>
<summary>📸 <b>Ver evidência visual: Testar mostrar senha</b></summary>
<br>
<img width="2554" height="1006" alt="testar mostrar senha" src="https://github.com/user-attachments/assets/b0c99483-0a77-43a4-a507-f4840b02e61e" />
</details>

<br>

#### 📌 **`@CT05_LUISA` - Tentativa de login com o campo de e-mail em branco**
* **Dado** que o usuário deixa o campo de e-mail em branco
* **Quando** tenta clicar no botão de prosseguir
* **Então** o sistema deve exibir um alerta exigindo o e-mail para continuar

<details>
<summary>📸 <b>Ver evidência visual: E-mail em branco</b></summary>
<br>
<img width="2557" height="1002" alt="email vazio" src="https://github.com/user-attachments/assets/7445702c-4d36-446d-b901-775f345a39b6" />
</details>

<br>

#### 📌 **`@CT06_LUISA` - Validar limite mínimo de caracteres para a senha**
* **Dado** que o usuário tenta cadastrar ou alterar sua senha
* **Quando** insere uma senha com quantidade de caracteres inferior ao permitido
* **Então** o sistema exibe alerta informando os requisitos mínimos de segurança

<details>
<summary>📸 <b>Ver evidência visual: Limite mínimo de caracteres na senha</b></summary>
<br>
<img width="2546" height="751" alt="testar limite minimo de caracteres" src="https://github.com/user-attachments/assets/6d49f37e-313f-4c38-9aec-e2b7c7d5569a" />
</details>

---
---

## 📑 Cenários de Teste & Evidências Visuais

#### 📌 **`@CT01_ML` - Autocompletar na busca por palavra-chave**
* **Dado** que o usuário está na página inicial do Mercado Livre
* **Quando** começa a digitar "notebook" no campo de busca
* **Então** o sistema deve exibir sugestões de autocompletar e categorias relacionadas

<details>
<summary>📸 <b>Ver evidência visual: Autocompletar na busca</b></summary>
<br>
<img width="1260" height="887" alt="FILTRO NOTEBOOK" src="https://github.com/user-attachments/assets/31a9bd23-3269-46e3-acf6-5bb590da956b" />
</details>

<br>

#### 📌 **`@CT02_ML` - Busca geral com resultados válidos**
* **Dado** que o usuário digita o termo "notebook" e confirma a pesquisa
* **Quando** a página de resultados é carregada
* **Então** o sistema exibe os produtos correspondentes e a contagem de resultados

<details>
<summary>📸 <b>Ver evidência visual: Busca com resultados válidos</b></summary>
<br>
<img width="1255" height="933" alt="FILTRO NOTEBOOK COM RESULTADO" src="https://github.com/user-attachments/assets/18bd2501-1c56-4d6b-81de-15e3718f537e" />
</details>

<br>

#### 📌 **`@CT03_ML` - Busca por termo inexistente**
* **Dado** que o usuário digita um termo aleatório e inexistente (ex: "akjbnjsb")
* **Quando** executa a pesquisa
* **Então** o sistema deve exibir a mensagem "Não encontramos resultados para a sua busca" com dicas de navegação

<details>
<summary>📸 <b>Ver evidência visual: Busca sem resultados</b></summary>
<br>
<img width="1257" height="924" alt="busca de algo inexistente" src="https://github.com/user-attachments/assets/d3eb82a5-e23c-48bd-b7a2-1cb5986c69c1" />
</details>

<br>

#### 📌 **`@CT04_ML` - Aplicar filtro de pesquisa por marca**
* **Dado** que o usuário está na lista de resultados da busca por notebooks
* **Quando** seleciona uma marca específica no menu lateral (ex: "Samsung")
* **Então** a lista de produtos é atualizada exibindo apenas itens da marca selecionada

<details>
<summary>📸 <b>Ver evidência visual: Filtro por marca</b></summary>
<br>
<img width="1264" height="930" alt="filtro notebook por marca" src="https://github.com/user-attachments/assets/9808ec6c-cd5d-475f-a72d-514f3d054578" />
</details>

<br>

#### 📌 **`@CT05_ML` - Aplicar filtro de faixa de preço**
* **Dado** que o usuário está na página de resultados de busca
* **Quando** aplica um filtro de intervalo de preço
* **Então** o sistema exibe somente os produtos compreendidos nessa faixa de valor

<details>
<summary>📸 <b>Ver evidência visual: Filtro de faixa de preço</b></summary>
<br>
<img width="2557" height="988" alt="FILTRO PREÇO" src="https://github.com/user-attachments/assets/f18a77da-4853-4659-8880-e77bdf4be32d" />
</details>

<br>

#### 📌 **`@CT06_ML` - Ordenar resultados da busca por menor preço**
* **Dado** que o usuário está visualizando a lista de produtos
* **Quando** altera a ordenação para "Menor preço"
* **Então** o sistema reordena a exibição exibindo os produtos do menor valor para o maior

<details>
<summary>📸 <b>Ver evidência visual: Ordenar por menor preço</b></summary>
<br>
<img width="2550" height="996" alt="ORDENAR POR MENOR PREÇO" src="https://github.com/user-attachments/assets/f12cf35d-ff27-47d9-ab86-29dc2d5f0920" />
</details>

---
---


### 📑 Cenários de Teste & Evidências Visuais

#### 📌 **`@CT01_AZ` - Validar a visibilidade da opção de login na barra superior**
* **Dado** que o usuário está na página inicial da Amazon Brasil
* **Quando** visualiza o cabeçalho da página
* **Então** a funcionalidade e botão "Faça seu login" deve estar claramente visível e acessível

<details>
<summary>📸 <b>Ver evidência visual: Botão de login visível</b></summary>
<br>
<img width="2555" height="1038" alt="botão de login" src="https://github.com/user-attachments/assets/83080b59-d0c9-4702-b11b-8d57229adc01" />
</details>

<br>

#### 📌 **`@CT02_AZ` - Verificar a presença e clareza da barra de busca principal**
* **Dado** que o usuário acessa a página inicial da Amazon
* **Quando** inspeciona o topo da tela
* **Então** a barra de busca deve apresentar visualização clara e pronta para recebimento de termos

<details>
<summary>📸 <b>Ver evidência visual: Barra de busca principal</b></summary>
<br>
<img width="2547" height="1029" alt="Barra de busca" src="https://github.com/user-attachments/assets/addc2dea-4263-43f3-b5e4-a2c7dd52a17b" />
</details>

<br>

#### 📌 **`@CT03_AZ` - Expandir o menu lateral "Todos" para navegação por categorias**
* **Dado** que o usuário está na página inicial
* **Quando** clica no botão de menu "Todos" no canto superior esquerdo
* **Então** o menu lateral responsivo deve se abrir exibindo a lista de produtos, categorias e recursos

<details>
<summary>📸 <b>Ver evidência visual: Menu lateral de categorias expandido</b></summary>
<br>
<img width="2560" height="1037" alt="Menu" src="https://github.com/user-attachments/assets/2e113cac-cbca-4026-84af-96905f3d02e7" />
</details>

<br>

#### 📌 **`@CT04_AZ` - Navegação a partir de banners publicitários e carrossel**
* **Dado** que o usuário visualiza os banners promocionais da Home
* **Quando** clica no banner promocional do produto (ex: "Pilhas Duracell")
* **Então** o sistema deve redirecionar corretamente para a página de destino da campanha

<details>
<summary>📸 <b>Ver evidência visual: Navegação via banners promocionais</b></summary>
<br>
<img width="2551" height="1034" alt="banners e carrosseis 2" src="https://github.com/user-attachments/assets/bc962a97-6b38-4d82-b3de-3c687c7d9d4e" />
</details>

<br>

#### 📌 **`@CT05_AZ` - Validar consistência de layout, alinhamentos e contraste da Home**
* **Dado** que o usuário carrega a página inicial da Amazon
* **Quando** analisa a disposição dos elementos visuais
* **Então** não deve haver erros de alinhamento, espaçamentos sobrepostos ou problemas de contraste

<details>
<summary>📸 <b>Ver evidência visual: Validação de layout e contraste</b></summary>
<br>
<img width="2558" height="991" alt="alinhamentos, espaçamentos e contraste" src="https://github.com/user-attachments/assets/a9f202a8-2569-46cb-b960-156620f4d752" />
</details>

<br>

#### 📌 **`@CT06_AZ` - Acionamento do menu suspenso em "Contas e Listas" via hover**
* **Dado** que o usuário está na página inicial
* **Quando** posiciona o ponteiro do mouse sobre o elemento "Contas e Listas"
* **Então** o menu suspenso (dropdown) deve ser exibido instantaneamente na tela

<details>
<summary>📸 <b>Ver evidência visual: Menu suspenso Contas e Listas via hover</b></summary>
<br>
<img width="2560" height="994" alt="banners e carrosseis" src="https://github.com/user-attachments/assets/33e813ef-34ca-4300-aeeb-2893ba714407" />
</details>
