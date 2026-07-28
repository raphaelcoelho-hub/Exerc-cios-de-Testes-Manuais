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

Abaixo está o registro consolidado das validações manuais executadas na suíte de regressão:

| Módulo | Funcionalidade | Cenário / Tag Principal | Status | Evidência Visual |
| :--- | :--- | :--- | :---: | :---: |
| **01. LinkedIn** | Cadastro & Autenticação | `@CT06_LI` Login Sucesso (Feed) | 🟢 PASSED | [Ver Evidência](#-01-linkedin) |
| **02. Magazine Luiza** | Autenticação & Segurança | `@CT04_LUISA` Alternar Máscara de Senha | 🟢 PASSED | [Ver Evidência](#-02-magazine-luiza) |
| **03. Mercado Livre** | Busca & Filtros de Preço | `@CT05_ML` Aplicação de Filtros | 🟢 PASSED | [Ver Evidência](#-03-mercado-livre) |
| **04. Amazon Brasil** | UI & Navegação por Categoria | `@CT03_AZ` Menu Lateral Responsivo | 🟢 PASSED | [Ver Evidência](#-04-amazon-brasil) |

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

















