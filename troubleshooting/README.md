# troubleshooting/

Registro de **problemas reais** que aconteceram no lab e como foram resolvidos.
Isso vale ouro: mostra pensamento, diagnóstico e método.

## O que entra aqui
- Erros de rede (NAT/Host-only, DHCP, DNS, gateway)
- Problemas de domínio (join falhando, GPO não aplica, DNS errado)
- Sysmon/Logging não coletando
- Problemas de permissões/UAC
- Qualquer “bug” que você resolveu e documentou

## Modelo de arquivo (padrão)
Cada issue deve ter:
- Sintoma
- Contexto (o que estava tentando fazer)
- Hipóteses testadas
- Passos (o que funcionou)
- Causa raiz (se souber)
- Prevenção (o que mudar pra não repetir)

## Nome de arquivo sugerido
- `win11-sem-internet-apos-dhcp.md`
- `domain-join-erro-ldap.md`