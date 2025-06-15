# az-104
Anotaçoes de estudo do AZ-104


Administrar Identidades

Microsoft entra ID seria o nome atualizado do Active Directory

Protocolos

Windows Server Administrar
AUTH
Kerberos
NTLM


Microsoft Entra ID
AUTH
SAML
OAUTH
Open ID
WS-Federation

Identidade hibrida, ele existe local, e foi migrado pra nuvem
__________________________________________________________________________

Network Security Group (NSG) – Um grupo de segurança de rede usado em ambientes de computação em nuvem, como o Microsoft Azure. 
Ele funciona como um firewall lógico, filtrando o tráfego de entrada e saída para proteger recursos de rede

__________________________________________________________________________

LRS (Locally Redundant Storage): Mantém três cópias dos dados dentro de um único datacenter na região primária. 
É a opção mais econômica, mas oferece menor proteção contra falhas regionais.

ZRS (Zone-Redundant Storage): Replica os dados sincronamente em três zonas de disponibilidade dentro da mesma região. 
Protege contra falhas de um datacenter inteiro.

GRS (Geo-Redundant Storage): Armazena os dados localmente na região primária e os copia assincronamente para uma região secundária distante. 
Protege contra falhas regionais, mas o acesso à cópia secundária é limitado.

GZRS (Geo-Zone-Redundant Storage): Combina ZRS e GRS, replicando os dados em três zonas de disponibilidade na região primária e copiando-os para uma região secundária. 
Oferece alta disponibilidade e proteção contra desastres.

existem variações como RA-GRS e RA-GZRS, que permitem acesso de leitura aos dados na região secundária.
