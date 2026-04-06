# Eng Soft II - 💰 Gestão Financeira Inteligente

> Sistema para gerenciamento de renda com foco em usabilidade e segurança.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

---

## 🔗 Acesso rápido

<p align="center">
  <a href="#-resumo"><img src="https://img.shields.io/badge/Resumo-222?style=for-the-badge"></a>
  <a href="#-atores--personas"><img src="https://img.shields.io/badge/Atores/Personas-222?style=for-the-badge"></a>
  <a href="#-principais-dores"><img src="https://img.shields.io/badge/Principais dores-222?style=for-the-badge"></a>
  <a href="#tecnologias">
  <img src="https://img.shields.io/badge/Tecnologias-222?style=for-the-badge">
</a>
  <a href="#planos">
  <img src="https://img.shields.io/badge/Planos-222?style=for-the-badge">
</a>
  <a href="#prototipacao">
  <img src="https://img.shields.io/badge/prototipação-222?style=for-the-badge">
</a>
<a href="#membros">
  <img src="https://img.shields.io/badge/Membros da equipe-222?style=for-the-badge">
</a>
</p>

---

## 📖 Resumo
Aplicativo de **gestão financeira** desenvolvido para ajudar **usuários da classe C** e **microempreendedores (MEI)** a organizar suas finanças.  
O app coleta informações de movimentações financeiras através de **notificações do celular** (como notificações de bancos) e também permite **registro manual** de contas e gastos.  

👉 O sistema armazena os dados e apresenta ao usuário um **resumo claro** do que foi gasto, recebido e das contas a pagar, ajudando no controle financeiro.

---

## 👥 Atores / Personas
- Pessoas da **classe C** que desejam controlar melhor seus gastos mensais.  
- **Microempreendedores individuais (MEI)** que precisam acompanhar entradas e saídas de dinheiro.  
- Usuários que querem organizar **renda ativa** e **renda passiva**.
veja as personas aqui: <p align="center">
  <a href="./docs/personas.md">
    <img src="https://img.shields.io/badge/👤%20Personas-0088cc?style=for-the-badge">
  </a>
</p>

---

## 😣 Principais Dores
- ❌ Falta de controle sobre gastos e receitas.  
- ❌ Esquecimento de contas a pagar.  
- ❌ Dificuldade de visualizar quanto dinheiro entra e quanto sai.  
- ❌ Falta de organização financeira em um único lugar.  

---

## 🛠️ Tecnologias <a name="tecnologias"></a>
- **Plataforma:** Android e iOS  
- **Linguagens:** JavaScript, React Native  
- **Banco de Dados:** Firebase 

---

## 💰 Planos <a name="planos"></a>

O **FechaConta** oferece um plano gratuito e opções premium com funcionalidades avançadas para melhor controle financeiro.

---

| Plano | Preço | Funcionalidades |
|------|------|----------------|
| 🆓 **Plano Gratuito** | - | - Registro manual de receitas e despesas<br>- Visualização de saldo total<br>- Histórico de transações<br>- Categorias básicas<br>- Relatórios simples<br>- Gráficos básicos |
| 💎 **Plano Premium Mensal** | R$ 9,90/mês | - Todas as funcionalidades do plano gratuito<br>- Criação de orçamentos por categoria<br>- Alertas de limite de gastos<br>- Lembretes de contas a pagar<br>- Metas financeiras<br>- Exportação de dados (PDF/CSV)<br>- Sem anúncios |
| 💎 **Plano Premium Semestral** | R$ 54,90/6 meses | - Todas as funcionalidades premium<br>- Desconto no valor total (~10%)<br>- Suporte prioritário |
| 💎 **Plano Premium Anual** | R$ 99,90/ano | - Todas as funcionalidades premium<br>- Maior desconto (~15%)<br>- Suporte prioritário<br>- Acesso antecipado a novas funcionalidades |

---

## 📱 Prototipação <a name="protipacao"></a>

Esta seção apresenta a relação entre as telas do aplicativo **FechaConta** e os requisitos funcionais e não funcionais definidos no projeto.
veja a seguir os requisitos: <p align="center">
  <a href="./docs/requisitos.md">
    <img src="https://img.shields.io/badge/📨%20Requisitos-0088cc?style=for-the-badge">
  </a>
</p>

link do Google Stitch: https://stitch.withgoogle.com/projects/1611214365353690810?pli=1

imagens do prototipo:

<img width="400" height="1000" alt="orcamento" src="https://github.com/user-attachments/assets/05668320-bcd9-43a2-991e-d5c75dc1f55f" />
<img width="400" height="1000" alt="login" src="https://github.com/user-attachments/assets/01822697-6004-4f3d-9675-ca07d83ca4de" />
<img width="400" height="1000" alt="historico" src="https://github.com/user-attachments/assets/ecae20df-2727-483e-af5c-a4f497cbf61b" />

---

### 📱 Tela 1: Login e Cadastro

- **RF01 — Cadastrar e Autenticar**  
  Campos de E-mail/Senha e o link "Cadastrar" no rodapé.

- **RNF05 — Autenticação Segura**  
  Ícone de biometria (autenticação rápida) e selo de conexão **256-bit SSL**.

---

### 📱 Tela 2: Dashboard (Início)

- **RF05 — Saldo Consolidado**  
  Exibição do saldo total em destaque.

- **RF02 / RF03 — Receitas e Despesas**  
  Cards com resumo financeiro.

- **RF06 — Histórico**  
  Seção "Últimas Atividades" com transações recentes.

- **RF13 — Notificações**  
  Ícone de sino e alerta de pagamento próximo.

---

### 📱 Tela 3: Novo Lançamento

- **RF02 / RF03 — Registrar Transações**  
  Seleção entre receita e despesa.

- **RF04 — Categorizar**  
  Botões de categorias (ex: Alimentação, Transporte).

- **RF14 — Múltiplas Contas**  
  Seleção de conta (corrente, poupança, etc.).

---

### 📱 Tela 4: Relatórios

- **RF08 — Relatórios Periódicos**  
  Filtros por período (Mês / Semana / Ano).

- **RF09 — Gráficos**  
  Visualização de dados financeiros.

- **RF11 — Alertas de Orçamento**  
  Indicador de meta de gastos.

---

### 📱 Tela 5: Planejamento (Orçamento)

- **RF10 — Orçamento por Categoria**  
  Definição de limites financeiros.

- **RF11 — Alertas de Excesso**  
  Avisos quando o orçamento é ultrapassado.

---

### 📱 Tela 6: Minhas Metas

- **RF17 — Definir Metas**  
  Criação de objetivos financeiros.

- **RF18 — Acompanhar Progresso**  
  Barras de progresso e porcentagens.

---

### 📱 Tela 7: Gerenciamento de Contas

- **RF14 — Múltiplas Contas**  
  Visualização e controle de diferentes contas.

---

### 📱 Tela 8: Ajustes (Configurações)

- **RF15 — Exportar Dados**  
  Opções para exportação (PDF, CSV, Excel).

- **RF16 — Importar Dados**  
  Upload de arquivos financeiros.

- **RNF05 — Segurança**  
  Configuração de biometria e alteração de senha.

---

### 📱 Tela 9: Lembretes

- **RF12 — Configurar Lembretes**  
  Definição de alertas de vencimento.

---

### 📱 Tela 10: Histórico Completo

- **RF06 — Histórico**  
  Lista cronológica de transações.

- **RF07 — Editar/Excluir**  
  Menu de opções por transação.

---

## ⚙️ Requisitos Não Funcionais Evidenciados

- **RNF07 — Usabilidade**  
  Interface consistente e intuitiva em todas as telas.

- **RNF15 — Precisão dos Dados**  
  Cálculos financeiros corretos e coerentes entre receitas, despesas e saldo total.

## 👨‍💻 Membros da Equipe <a name="membros"></a>
| Nome                          | RA             |
|-------------------------------|----------------|
| Allan Batista Dos Santos      | 0030482511042 |
| Bruno Rocha Wendland          | 0030482511028 |
| Leonardo Akira Ikeda Son      | 0030482511030 |
| Murillo Alves Lourenço        | 0030482511006 |
