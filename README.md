# OpenSaldo

Painel de finanças pessoais e patrimônio que roda dentro do Claude. Uma página só, cifrada, que junta contas, cartões, assinaturas, previstos, bens, investimentos e empresas, e um agente que fica mais útil quanto mais contexto você dá a ele.

> **Status:** em construção, sem versão publicada. O painel já roda; as skills do plugin vêm em seguida.

## O que ele faz

- **Tudo num lugar:** contas, cartões e faturas, transações com busca e agrupamento, assinaturas, gastos fixos, parcelas, receitas e despesas previstas.
- **Timeline:** passado reconstruído e projeção mês a mês, pela compra ou pelo vencimento da fatura.
- **Patrimônio:** imóveis, carros e investimentos com simuladores (valorização, custo real de manter, rendimento).
- **Grupos:** viagens, compras, negócios e reembolsos explicam os meses fora da curva.
- **Empresas (PJ):** separa o que é da empresa do que é seu e mostra pró-labore, distribuição e reembolsos.
- **Casal:** responsabilidades por gasto, contas conjuntas e o acerto do mês.
- **Automações:** relatórios e alertas por e-mail, Slack ou WhatsApp, agendados pelo Claude.

## Segurança

- Os dados ficam cifrados na própria página (AES-256-GCM). A chave é aberta só no seu navegador, com a sua senha.
- Integração com bancos pelo Open Finance regulado pelo Banco Central: o painel nunca vê a senha do banco.
- Modo anônimo borra todos os valores em um clique.
- Nenhum dado financeiro vive neste repositório.

## Estrutura

```
opensaldo/
├─ .claude-plugin/plugin.json   identidade do plugin
├─ skills/                      uma pasta por skill (em construção)
└─ docs/                        documentação
```

## Instalação (quando sair a primeira versão)

O OpenSaldo vai ser distribuído pelo marketplace público da NOVARC:

```
/plugin marketplace add NovArc-Sistemas/novarc-dev
/plugin install opensaldo@novarc-dev
```

## Licença

MIT. Feito pela [NOVARC Sistemas](https://www.novarcsistemas.com).
