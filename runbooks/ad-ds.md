# GERENCIAMENTO ACTIVE DIRECTORY DOMAIN SERVICE

O Active Directory Domain Service (AD) é extremamente essencial, permite com que faça o gerenciamento de usuários, grupos e permissões.

Neste serviço, é utilizado o protocolo Ldap, que permite que as configurações sejam replicadas para todos os servidores do domínio. Deste modo, se perder os dados como políticas, dados e permissões, poderá ter um segundo, terceiro, quarto...., com os mesmos objetos.

A respeito de autenticação, o Active Directory utiliza o protocolo Kerberos, que permite que o usuário logue em qualquer computador que esteja dentro do domínio ou florestas de domínios.

================================================

# ACTIVE DIRECTORY NA PRÁTICA

Verifique sempre as configurações de rede, utilize sempre as ferramentas do windows (Windows Tools) e o Server Manager. Em estudo com VMs, o padrão utilizado foi duas placas de rede para Windows Server, a externa (NAT) e interna (Host-Only). Já no Windows 11 apenas uma placa de rede (Host-Only).

# ADMINISTRAÇÃO DE USUÁRIOS E GRUPOS

-Crie um domínio

-Dentro do domínio, crie um "organization unit"

-Na sua "organization unit", crie grupos e crie usuários

-Escolha qual vai ser o tipo de senha para o usuário

-É sempre importante definir uma primeira senha com letras, números e símbolos que não seja pequena. 

-Adicione usuários aos grupos em que devem pertencer 

-Pode-se criar scripts específicos a cada grupo, permissões a pastas, etc

-Sempre gerencie por grupos, e não usuários, então permissões são destinadas à grupos.

# ADICIONANDO UM COMPUTADOR AO DOMÍNIO

-Ao definir o IP do Windows Server, deixe seu próprio IP como gateway e DNS.

-No Windows 11, defina um IP que esteja dentro da mesma rede do Windows Server, também coloque o IP do servidor como gateway e DNS.

-Em System -> Workgroup/domain - Altere para o nome do domínio do servidor, insira as credenciais de Administrador e reinicie o computador.

-Por final, entre com as credenciais definidas do usuário e estará dentro do domínio.
