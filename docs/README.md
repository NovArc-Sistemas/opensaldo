# Documentação do OpenSaldo

> Em construção. Esta página cresce junto com as skills.

## Como o painel funciona

- **Uma página só, cifrada.** Os dados ficam dentro do próprio Artifact, cifrados com AES-256-GCM. A chave é derivada da sua senha e aberta só no seu navegador.
- **Bancos pelo Open Finance.** A conexão passa pelo Open Finance regulado pelo Banco Central, por um conector do [mcplace](https://mcplace.com.br). O painel nunca vê a senha do banco.
- **O Claude mantém em dia.** Uma rotina diária busca os bancos, recalcula a timeline e republica a página. O que a interface não faz sozinha, você pede pela barra de comandos (Ctrl K).

## Telas

Visão geral, Timeline, Transações, Contas e cartões, Compromissos, Grupos, Entidades, Previstos, Empresas, Casal, Visão do patrimônio, Bens, Investimentos, Automações e Conectar dados.

## Privacidade

Nenhum dado financeiro vive neste repositório. O modo anônimo borra os valores da tela em um clique.
