# 📘 Diagrama de Caso de Uso — Sistema de Controle Financeiro

```mermaid
flowchart LR
    %% Atores
    Usuario([Usuário])
    Notificacao([Sistema de Notificação])
    Integracao([Serviço de Integração])

    %% Casos de Uso
    subgraph Sistema_de_Controle_Financeiro
        UC1((Cadastrar Conta))
        UC2((Autenticar Usuário))
        UC15((Gerenciar Contas))

        UC3((Registrar Receita))
        UC4((Registrar Despesa))
        UC5((Categorizar Transações))
        UC6((Gerenciar Transações))

        UC7((Visualizar Histórico))
        UC8((Exibir Saldo))
        UC9((Gerar Relatórios))
        UC10((Visualizar Gráficos))

        UC11((Definir Orçamento))
        UC12((Alerta de Orçamento))
        UC13((Configurar Lembretes))
        UC14((Enviar Notificações))

        UC16((Exportar Dados))
        UC17((Importar Dados))
        UC18((Definir Metas))
        UC19((Acompanhar Metas))
    end

    %% Ligações com Usuário
    Usuario --> UC1
    Usuario --> UC2
    Usuario --> UC3
    Usuario --> UC4
    Usuario --> UC6
    Usuario --> UC7
    Usuario --> UC8
    Usuario --> UC9
    Usuario --> UC11
    Usuario --> UC13
    Usuario --> UC15
    Usuario --> UC18

    %% Ligações com Sistemas Externos
    Notificacao --> UC14
    Integracao --> UC16
    Integracao --> UC17

    %% Relacionamentos (simulados como setas)
    UC6 --> UC3
    UC6 --> UC4
    UC3 --> UC5
    UC4 --> UC5
    UC9 --> UC7
    UC10 --> UC7
    UC12 --> UC11
    UC14 --> UC13
    UC19 --> UC18
