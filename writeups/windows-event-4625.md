# Caso: Windows Event 4625 (Falha de logon)

## Contexto
O que aconteceu? Onde foi visto? (simulado/lab)

## Evidências
- Event ID: 4625
- Campos relevantes: Account Name, Logon Type, Source Network Address

## Passos de triagem
1) Filtrar no Event Viewer
2) Contar repetição (mesmo IP? mesmo usuário?)
3) Ver correlação com 4624 (sucesso) e 4648 (logon explícito), se existir

## Conclusão
Hipótese + próximos passos