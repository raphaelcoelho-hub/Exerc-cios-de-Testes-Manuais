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


## Especificação BDD / Gherkin & Evidências

### 01. LinkedIn

```gherkin
<!-- CT01_LI: Acessar a página de criação de conta -->
<details>
<summary>📸 <b>Ver evidência visual: Acessar página de criar conta</b></summary>
<br>
<img width="2560" height="998" alt="abrir criar conta" src="https://github.com/user-attachments/assets/891f8a1e-5292-4784-9393-39065f5c9220" />
</details>

<br>

<!-- CT02_LI: Tentativa de login com e-mail em formato inválido -->
<details>
<summary>📸 <b>Ver evidência visual: E-mail com formato inválido</b></summary>
<br>
<img width="2560" height="982" alt="EMAIL COM FORMATO INVÁLIDO" src="https://github.com/user-attachments/assets/18f7c1c7-f04a-4e7c-91e2-8956a049a05e" />
</details>

<br>

<!-- CT03_LI: Login mantendo campo de e-mail vazio -->
<details>
<summary>📸 <b>Ver evidência visual: Login com campo de e-mail vazio</b></summary>
<br>
<img width="2560" height="994" alt="Login com campo de email vazio" src="https://github.com/user-attachments/assets/28bb1924-644a-4791-be95-c6b95d052204" />
</details>

<br>

<!-- CT04_LI: Login mantendo campo de senha vazio -->
<details>
<summary>📸 <b>Ver evidência visual: Login com campo de senha vazio</b></summary>
<br>
<img width="2554" height="995" alt="login com campo de senha vazia" src="https://github.com/user-attachments/assets/f59912e5-8d44-47f4-afd9-cce45801d703" />
</details>

<br>

<!-- CT05_LI: Senha abaixo do limite de caracteres -->
<details>
<summary>📸 <b>Ver evidência visual: Validação de senha curta</b></summary>
<br>
<img width="2558" height="990" alt="senha curta, sem numero" src="https://github.com/user-attachments/assets/99b44779-1342-441e-b183-de434e2f4396" />
</details>

<br>

<!-- Comportamento dos Botões "Continuar" -->
<details>
<summary>📸 <b>Ver evidência visual: Comportamento dos botões Continuar</b></summary>
<br>
<img width="2560" height="990" alt="Verificar comportamento dos botões “Continuar” 1" src="https://github.com/user-attachments/assets/9073ea9d-99bb-4010-853f-dcb6cbc316af" />
<br><br>
<img width="2588" height="359" alt="Verificar comportamento dos botões “Continuar” 2" src="https://github.com/user-attachments/assets/8c2009da-d8ec-4bcd-80af-8d39e507f5f2" />
</details>

---

```gherkin

<!-- CT01_LUISA: E-mail correto com senha incorreta -->
<details>
<summary>📸 <b>Ver evidência visual: E-mail correto e senha errada</b></summary>
<br>
<img width="2556" height="992" alt="EMAIL CORRERO COM SENHA ERRADA" src="https://github.com/user-attachments/assets/aa171546-c4b3-49d3-8676-889264f0f6fc" />
</details>

<br>

<!-- CT02_LUISA: E-mail sem o "@" -->
<details>
<summary>📸 <b>Ver evidência visual: E-mail sem '@'</b></summary>
<br>
<img width="2556" height="992" alt="email sem o arroba com senha correta" src="https://github.com/user-attachments/assets/b94329c6-ac35-47f9-8566-5719c46909b2" />
</details>

<br>

<!-- CT03_LUISA: E-mail correto com campo de senha vazio -->
<details>
<summary>📸 <b>Ver evidência visual: E-mail correto com campo de senha vazio</b></summary>
<br>
<img width="2547" height="893" alt="email correto com campo de senha vazio" src="https://github.com/user-attachments/assets/2c661245-4873-40c1-bf03-63a3bef41d79" />
</details>

<br>

<!-- CT04_LUISA: Mostrar/Ocultar senha -->
<details>
<summary>📸 <b>Ver evidência visual: Testar mostrar senha</b></summary>
<br>
<img width="2554" height="1006" alt="testar mostrar senha" src="https://github.com/user-attachments/assets/b0c99483-0a77-43a4-a507-f4840b02e61e" />
</details>

<br>

<!-- CT05_LUISA: E-mail em branco -->
<details>
<summary>📸 <b>Ver evidência visual: E-mail em branco</b></summary>
<br>
<img width="2557" height="1002" alt="email vazio" src="https://github.com/user-attachments/assets/7445702c-4d36-446d-b901-775f345a39b6" />
</details>

<br>

<!-- CT06_LUISA: Limite mínimo de caracteres -->
<details>
<summary>📸 <b>Ver evidência visual: Limite mínimo de caracteres na senha</b></summary>
<br>
<img width="2546" height="751" alt="testar limite minimo de caracteres" src="https://github.com/user-attachments/assets/6d49f37e-313f-4c38-9aec-e2b7c7d5569a" />
</details>
















