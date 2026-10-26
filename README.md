# CGNAT Map Generator (Fixed-NAT)

Gerador web de mapeamento determinístico de portas CGNAT (Fixed-NAT) em conformidade com a **RFC 6598**, voltado para operação de redes ISP e engenharia de borda.

## Recursos e Novidades da Versão 5
- **Campos Avançados do MikroTik:** 
  - Seleção de Versão do RouterOS (`v6` / `v7`).
  - Configuração de Interface LAN (*In-Interface*) com opção de ativação, desativação ou uso de lista de interfaces.
  - Configuração de Interface WAN (*Out-Interface*) com suporte a nome específico ou lista.
  - Bypass de Tráfego Local com opção de rede/lista e flag para regra em NAT/RAW.
  - Rotas de Blackhole customizáveis (`blackhole`, `unreachable` ou `gateway/interface`).
  - Definição customizada do nome da Chain de CGNAT (*jump-target*).
  - Suporte a *Out-Interface* nas regras privadas.
- **Lógica Otimizada de Mapeamento:** Mapeamento determinístico sequencial com suporte ampliado a qualquer máscara CIDR em blocos públicos (sem restrição a `/24`, suportando `/23`, `/22`, etc.).
- **Suporte a A10 Networks:** Seletor de plataforma integrado para alternar perfeitamente entre MikroTik e A10 Networks.
- **Busca, Filtros e Exportação:** Ferramentas de busca por IP:PORTA, filtros por coluna estilo planilha e exportação CSV.
