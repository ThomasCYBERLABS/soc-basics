# GERENCIAMENTO ACTIVE DIRECTORY DOMAIN SERVICE

O Active Directory Domain Service (AD) é extremamente essencial, permite com que faça o gerenciamento de usuários, grupos e permissões.

Neste serviço, é utilizado o protocolo Ldap, que permite que as configurações sejam replicadas para todos os servidores do domínio. Deste modo, se perder os dados como políticas, dados e permissões, poderá ter um segundo, terceiro, quarto...., com os mesmos objetos.

A respeito de autenticação, o Active Directory utiliza o protocolo Kerberos, que permite que o usuário logue em qualquer computador que esteja dentro do domínio ou florestas de domínios.

================================================

# ACTIVE DIRECTORY NA PRÁTICA

1 - Crie um domínio

2 - Dentro do domínio, crie um "organization unit"

3 - Na sua "organization unit", crie grupos e crie usuários

4 - Escolha qual vai ser o tipo de senha para o usuário

5 - É sempre importante definir uma primeira senha com letras, números e símbolos que não seja pequena. 

6 - Adicione usuários aos grupos em que devem pertencer 

7 - Pode-se criar scripts específicos a cada grupo, permissões a pastas, etc

8 - Sempre gerencie por grupos, e não usuários, então permissões são destinadas à grupos.
