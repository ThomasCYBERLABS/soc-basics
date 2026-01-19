# scripts/

Scripts para **automatizar tarefas repetitivas** do lab (triagem, parsing, enriquecimento, relatórios).
Prioridade: scripts simples que economizam tempo e geram artefatos.

## Tipos de scripts esperados
- Parser de logs -> CSV (filtrar, contar, agrupar)
- Extração de IOCs (IPs/domínios/hashes) de texto/log
- Enriquecimento básico (DNS/WHOIS) para lista de indicadores
- Relatórios automáticos (resumo + top N)

## Estrutura sugerida
- `scripts/python/`
- `scripts/powershell/`
- `scripts/utils/` (helpers)

## Regras
- Script deve ter README curto no topo ou comentário de uso:
  - o que faz
  - input esperado
  - como rodar
  - output gerado
- Nunca suba credenciais, tokens, chaves ou dados sensíveis
