# writeups/

Writeups são **investigações** (estilo SOC): você parte de um alerta/dado e produz uma conclusão com evidências.
Isso é o que mais “vende” seu perfil.

## O que entra aqui
- Investigação de eventos do Windows (ex.: 4625, 4624, 4688, 7045)
- Análises de PCAP (DNS/HTTP/TLS básicos)
- Casos de IOC (domínio/IP suspeito -> enriquecimento -> decisão)
- Pequenos “cases” simulados (ataque e detecção no lab)

## Modelo (padrão de writeup)
1) Contexto (alerta/caso)
2) Evidências (prints/queries/comandos)
3) Linha do tempo (se aplicável)
4) Hipótese(s) e validação
5) Conclusão (falso positivo vs incidente)
6) Próximos passos (recomendação)

## Regras
- Curto e objetivo: 1–2 páginas em Markdown já é suficiente
- Não inventar história: se não sabe, registra como “limitação”