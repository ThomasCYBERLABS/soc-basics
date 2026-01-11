GERENCIAMENTO ACTIVE DIRECTORY DOMAIN SERVICE

-O Active Directory Domain Service (AD) é extremamente essencial, permite com que faça o gerenciamento de usuários, grupos e permissões.

-Neste serviço, é utilizado o protocolo Ldap, que permite que as configurações sejam replicadas para todos os servidores do domínio. Deste modo, se perder os dados como políticas, dados e permissões, poderá ter um segundo, terceiro, quarto...., com os mesmos objetos.

-A respeito de autenticação, o Active Directory utiliza o protocolo Kerberos, que permite que o usuário logue em qualquer computador que esteja dentro do domínio ou florestas de domínios.


# ACTIVE DIRECTORY NA PRÁTICA

# 1 - CRIE UM DOMÍNIO
# 2 - DENTRO DO DOMÍNIO, CRIE UM "ORGANIZATION UNIT"
# 3 - DENTRO DA SUA "ORGANIZATION UNIT", CRIE GRUPOS E CRIE USUÁRIOS
# 4 - ESCOLHA QUAL VAI SER O TIPO DE SENHA PARA O USUÁRIO
# 5 - É SEMPRE IMPORTANTE DEFINIR UMA PRIMEIRA SENHA COM LETRAS, NÚMEROS E SÍMBOLOS QUE NÃO SEJA PEQUENA. 
# 6 - ADICIONE USUÁRIOS AOS GRUPOS EM QUE DEVEM PERTENCER 
# 7 - PODE-SE CRIAR SCRIPTS ESPECÍFICOS A CADA GRUPO, PERMISSÕES A PASTAS, ETC
# 8 - SEMPRE GERENCIE POR GRUPOS, E NÃO USUÁRIOS, ENTÃO PERMISSÕES SÃO DESTINADAS À GRUPOS.
