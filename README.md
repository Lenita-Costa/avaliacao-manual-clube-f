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
```

## O que o painel mostra

Quando o sistema não reconhece o vínculo do usuário automaticamente (por e-mail
ou CPF), o caso segue para validação manual.

| Recorte | Casos | Liberados | Rejeitados | Pendentes |
|---|---|---|---|---|
| Ação do dia 13 — ASBAC Brasília | 46 | 44 (96%) | 0 | 2 |
| Histórico consolidado | 94 | 87 (93%) | 3 | 4 |

O painel abre ainda o perfil dos cadastros por tipo de vínculo, a distribuição
por regional e as vias de confirmação do vínculo.

**Leitura:** a barreira não foi falha do sistema. A maioria são associados
legítimos — em especial sócios contribuintes — que não constavam nas planilhas
das ASBACs ou constavam com dados divergentes. A inconsistência do dado na
origem é o que reforça a frente de qualidade das bases regionais (projeto
Conecta). Os pendentes dependem do retorno da própria pessoa, não da TI.

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
