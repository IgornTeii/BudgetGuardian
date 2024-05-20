# BudgetGuardian

## Descrição

BudgetGuardian é uma aplicação desenvolvida para ajudar você a controlar seus gastos mensais. Com essa ferramenta, você pode organizar seus gastos fixos e variáveis, calcular a soma total de seus gastos, receber lembretes de pagamento e ser avisado quando estiver próximo do seu limite de gastos estipulado por mês.

## Funcionalidades

- **Organização de Gastos**: Categorize seus gastos em fixos e variáveis.
- **Cálculo de Total**: Calcule a soma total de todos os seus gastos.
- **Lembretes de Pagamento**: Receba notificações de lembretes para pagar suas contas.
- **Alertas de Limite**: Seja avisado quando estiver próximo do seu limite de gastos mensal.

## Tecnologias Utilizadas

- **Front-end**: Next.js
- **Back-end**: Node.js, Express

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/budgetguardian.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd budgetguardian
    ```

3. Instale as dependências do back-end:

    ```bash
    cd backend
    npm install
    ```

4. Instale as dependências do front-end:

    ```bash
    cd ../frontend
    npm install
    ```

## Configuração

1. Crie um arquivo `.env` no diretório `backend` com as seguintes variáveis de ambiente:

    ```env
    DB_HOST=localhost
    DB_USER=seu-usuario
    DB_PASS=sua-senha
    DB_NAME=budgetguardian
    ```

2. Configure o arquivo `.env.local` no diretório `frontend` se necessário.

## Executando o Projeto

1. Inicie o servidor do back-end:

    ```bash
    cd backend
    npm start
    ```

2. Inicie o servidor do front-end:

    ```bash
    cd ../frontend
    npm run dev
    ```

3. Acesse a aplicação em seu navegador:

    ```
    http://localhost:3000
    ```

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
