# CGNAT Map Generator (Fixed-NAT)

Gerador web de mapeamento determinístico de portas CGNAT (Fixed-NAT) em conformidade com a **RFC 6598**, voltado para operação de redes ISP e engenharia de borda.

## Recursos e Novidades da Versão 2
- **Geração Automática de Scripts:** Suporte a exportação direta de comandos para MikroTik RouterOS (v6 e v7) e A10 Networks.
- **Busca Avançada:** Suporte a pesquisa por IP:PORTA (ex: `203.0.113.0:10718`) e verificação de intervalo de portas dinâmico.
- **Filtros e Ordenação:** Filtros em estilo planilha por coluna com caixas de seleção (*checkboxes*) e ordenação interativa.
- **Proteção e Flexibilidade:** Configuração de bypass de tráfego local, rotas de blackhole/loop prevention e proporções customizadas de portas por cliente.
- **Exportação CSV:** Exportação completa de tabelas filtradas ou brutas.
