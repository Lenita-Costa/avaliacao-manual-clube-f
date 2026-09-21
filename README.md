# Avaliação Manual — Clube F

Painel dos casos que caíram no fluxo de validação manual de vínculo do Clube F:
a ação presencial do dia 13 na ASBAC Brasília e a visão consolidada do histórico.
Coordenação de TI · Fenasbac.

## Dashboard

Publicado via GitHub Pages:

**https://lenita-costa.github.io/avaliacao-manual-clube-f/**

## Estrutura

```
index.html   painel de validação manual (publicado no Pages)
.nojekyll    desliga o Jekyll no Pages, serve o HTML como está
.gitignore   mantém o relatório .docx de origem fora do repositório público
```

## O que o painel mostra

Quando o sistema não reconhece o vínculo do usuário automaticamente (primeiro
por e-mail, depois por CPF, nas duas bases), o caso segue para validação manual.
O painel traz dois recortes:

| Recorte | Casos | Liberados | Rejeitados | Pendentes |
|---|---|---|---|---|
| Visão 1 — ação do dia 13 em diante · ASBAC Brasília | 46 | 44 (96%) | 0 | 2 |
| Visão 2 — consolidado, 02/07 a 21/09/2026 | 94 | 87 (93%) | 3 | 4 |

Cada recorte abre em motivo da decisão, via de confirmação e tipo de vínculo.
O painel traz ainda a distribuição por regional e a leitura final.

**Leitura:** a barreira não foi falha do sistema. Sócio contribuinte é o maior
motivo isolado — 31 dos 94 casos (33%), e 20 dos 46 do evento (43%). Os 31
foram confirmados pela mesma via, sem exceção: contato direto com a regional.
Nenhum saiu por consulta às bases, o que indica que a categoria não veio na
carga da integração. Some-se a isso a divergência de dado na origem (e-mail ou
CPF diferente do informado), e está explicado o volume da análise manual. Os
pendentes dependem do retorno da própria pessoa, não da TI.

## Fonte dos números

Aba `Casos` da planilha *Liberação de Acesso* (registro de solicitações do
Clube F). Os totais do painel conferem com as abas `Resumo` e `Acompanhamento
por ASBAC` da própria planilha. O recorte do evento é definido como casos da
ASBAC Brasília com data de contato a partir de 13/09/2026.

## Como atualizar

1. Editar o `index.html`.
2. Commit e push na `main` — o Pages atualiza automaticamente.

## Observação

Este repositório é público, portanto o painel fica acessível na internet por
quem tiver o link. Os números são agregados (contagens por status, por tipo de
vínculo e por regional); não há dados pessoais, nomes, CPF, e-mail ou
informação de acesso.

Os demais painéis de TI seguem em
[report-mensal-ti](https://github.com/Lenita-Costa/report-mensal-ti) (mensal) e
[relatorio-sprint](https://github.com/Lenita-Costa/relatorio-sprint) (quinzenal).
