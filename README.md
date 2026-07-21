# Logística Xperiun — Dashboard Power BI

## Descrição

Painel Power BI para monitoramento e insights de logística do cliente **XperiunLog**.

## Status

- **Estado:** Em desenvolvimento
- **Arquivo principal do relatório:** `Painel 20 - Logistica Xperiun Log.pbix`

## Estrutura do repositório

- `Base de Dados/` — fonte de dados (`Base de Dados.xlsx`).
- `Design/` — assets visuais (fundos de tela editáveis, imagens de apoio ao layout).
- `Painel 20 - Logistica Xperiun Log.pbix` — histórico/backup do painel.
- `Instruções.pdf` — instruções de uso/entrega do painel.

## Como abrir o projeto

1. Abra o Power BI Desktop e carregue o arquivo `Painel 20 - Logistica Xperiun Log.pbix`.
2. Se necessário, atualize as credenciais das fontes de dados em **Transform data → Data source settings**.

## Fontes de dados e atualização

**Fonte:** planilha Excel (`Base de Dados/Base de Dados.xlsx`).

_(preencher: descreva aqui a origem real dos dados nessa planilha — ex.: exportação manual de um sistema, ERP, WMS — e qualquer credencial/processo de acesso necessário.)_

**Procedimento para atualizar dados:**

1. Atualizar/exportar a fonte em `Base de Dados/Base de Dados.xlsx`.
2. No Power BI Desktop: **Home → Refresh**.
3. Salvar o arquivo `.pbix` e, se aplicável, exportar a versão para produção (Power BI Service).

## Versionamento e observações sobre `.pbix`

> **Aviso:** `.pbix` é um formato binário — diffs e merges não são possíveis. O histórico de mudanças no arquivo em si não é legível pelo Git.

- O `Painel 20 - Logistica Xperiun Log.pbix` **é versionado** neste repositório (ver `.gitignore`, que ignora apenas variantes de backup/autosave: `*_backup.pbix`, `*.pbix.autosave`, `*Painel 20 - Logistica Xperiun Log.pbix~`).
- Recomendação: commitar apenas versões estáveis/finais, evitando commits a cada pequena alteração de layout.
- Alternativa futura: migrar para o formato **PBIP** (Power BI Project — `Arquivo → Salvar como → Power BI Project`), que salva o modelo em arquivos texto (`.tmdl`/`.json`) e permite diff real no Git.

## Backup e histórico

- Salvar cópias de versão antes de alterações significativas.
- Nome sugerido: `Dashboard Logistica_YYYYMMDD.pbix`.
- O arquivo `Painel 20 - Logistica Xperiun Log.pbix` serve como histórico/backup consolidado.

## Como contribuir

1. Crie uma branch por alteração: `git checkout -b feat/descreva-a-mudanca`.
2. Documente as alterações neste README e no Changelog.
3. Abra um PR descrevendo as mudanças e os dados atualizados.

## Changelog

| Versão | Data    | Notas                                                                                                      |
| ------ | ------- | ---------------------------------------------------------------------------------------------------------- |
| v0.1   | 2026-07 | Estrutura inicial do repositório, `.gitignore` e versionamento do `Painel 20 - Logistica Xperiun Log.pbix` |

_(atualize esta tabela a cada entrega relevante)_

## Contato

- **Autor:** Nilvan Felipe
- **Email/Slack/Teams:** _(preencher)_

## Licença

_(preencher: adicione a licença desejada — ex.: MIT — ou remova esta seção caso o projeto seja de uso interno/proprietário.)_
