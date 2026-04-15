---
website: "Câmara Municipal de Sátão (sítio Web institucional)"          # Entre as aspas escreve o nome do website
date: "30/12/2025"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://www.cm-satao.pt"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://dominio_sitio_web.pt/acessibilidade" # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
owner: "Câmara Municipal de Sátão"         # Entre as aspas escrever o nome do owner do website
seal: "Ouro"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "_31/12/1999 a 31/12/2000_" # Entre as aspas escreve data de início e data de fim no formato 31/12/1999 a 31/12/2000
status: "Auditoria a decorrer" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório de Auditoria

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório {{ page.website }}</a></li>
    <li><a href="/report_012/25022026_report.html">(25/02/2026). Relatório do {{ page.website }}</a></li>
  </ul>
</details>
