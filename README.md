# CGNAT Map Generator (Fixed-NAT)

Gerador web de mapeamento determinístico de portas CGNAT (Fixed-NAT) em conformidade com a **RFC 6598**, voltado para operação de redes ISP e engenharia de borda.

## Recursos e Novidades da Versão 4
- **Correção de DOM e Estabilidade:** Reinsersão correta do elemento `<div id="renderLimitNotice">` no DOM logo abaixo do container da tabela rolável, eliminando erros de referência nula (*null reference*) durante filtros e atualizações de visualização.
- **Seletor de Plataforma Dinâmico:** Alternância integrada entre A10 Networks (ACOS v5.x) e MikroTik RouterOS (v6/v7).
- **Busca Avançada & Filtros:** Suporte a pesquisa por IP:PORTA, filtros em estilo planilha por coluna (*checkboxes*) e ordenação interativa.
- **Exportação CSV:** Exportação completa de tabelas tratadas ou brutas.
