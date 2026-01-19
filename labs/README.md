# labs/

Aqui ficam os **cenários do laboratório** (ambiente, topologia, VMs e configurações) usados para gerar dados reais: logs, alertas simulados e tráfego de rede.

## O que entra aqui
- Diagramas simples de rede (NAT/Host-only, IPs, DNS, DHCP)
- Inventário do ambiente (VMs, versões, roles)
- Procedimentos de setup (passo a passo)
- “Cenários” (ex.: Sysmon + coleta, ataque simulado, etc.)

## Estrutura sugerida
- `labs/01-ambiente/` → VMs, rede, snapshots
- `labs/02-windows-logging/` → Sysmon, auditoria, coleta
- `labs/03-rede-pcap/` → capturas e exercícios de PCAP
- `labs/99-anexos/` → prints, diagramas, configs

## Regras
- Nada de dado sensível (IPs públicos, usuários reais, chaves, etc.)
- Sempre que possível: print + 5 linhas explicando “o que foi feito e por quê”