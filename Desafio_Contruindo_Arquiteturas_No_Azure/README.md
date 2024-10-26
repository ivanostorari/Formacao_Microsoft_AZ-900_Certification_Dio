Ivan Wagner

# Construindo arquiteturas no Azure
Microsoft Azure: Construindo arquiteturas no Azure. Arquitetura global.

## Infraestrutura global do Azure
A infraestrutura global do Azure é composta por dois componentes principais: a infraestrutura física e os componentes de rede de conexão. O componente físico é composto por mais de  300  datacenters físicos, organizados em regiões e vinculados por uma das maiores redes interconectadas do planeta.

Com a conectividade da rede global do Azure, cada um dos datacenters do Azure fornece alta disponibilidade, baixa latência, escalabilidade e os avanços mais recentes na infraestrutura de nuvem. Tudo isso em execução na plataforma do Azure.

Juntos, esses componentes mantêm os dados completamente dentro da rede confiável da Microsoft e o tráfego IP nunca entra na Internet pública.

## Datacenter
Os datacenters do Azure são edifícios físicos exclusivos localizados em todo o mundo que abrigam um grupo de servidores de computador em rede.

## Região
A região do Azure é um conjunto de datacenters implantados dentro de um perímetro de latência definida e conectados por meio de uma rede regional dedicada de baixa latência.

Com mais regiões globais do que qualquer outro provedor de nuvem, o Azure dá aos clientes a flexibilidade para implantar aplicativos no local em que eles precisam. A região do Azure tem preços e disponibilidade de serviço distintos.

## Localização geográfica
A área geográfica do Azure é um mercado discreto, que normalmente contém pelo menos uma ou mais regiões, que preserva os limites de conformidade e de residência de dados. As geografias permitem que os clientes com necessidades de conformidade e de residência de dados específicas mantenham os dados e aplicativos próximos. As geografias são tolerantes a falhas para resistir a falhas completas da região por meio da sua conexão com a infraestrutura de rede dedicada e de alta capacidade do Azure.

## Zonas de disponibilidade
As Zonas de Disponibilidade do Azure são localizações físicas exclusivas dentro de uma região do Azure e oferecem alta disponibilidade para proteger os aplicativos e dados contra falhas do datacenter. Cada zona é composta por um ou mais datacenters equipados com energia, resfriamento e rede independentes.

A separação física das zonas de disponibilidade dentro de uma região protege os aplicativos e os dados contra problemas de nível de instalações. Os serviços com redundância de zona replicam os aplicativos e os dados entre Zonas de Disponibilidade do Azure para proteger dos pontos únicos de falha.

## Azure Edge Zones
Os Azure Edge Zones são extensões de volume do Azure, colocadas em áreas densamente populadas. Os Azure Edge Zones dão suporte a VMs (máquinas virtuais), contêineres e um conjunto selecionado de serviços do Azure que permitem que você execute aplicativos com uso intensivo de taxa de transferência e sensíveis à latência próximos aos usuários finais.

Os Azure Edge Zones fazem parte da rede global da Microsoft e oferecem conectividade segura, confiável e de alta largura de banda entre os aplicativos que estão em execução no Azure Edge Zone (perto do usuário) e um conjunto completo de serviços do Azure em execução nas maiores regiões do Azure.

## Ponto de presença
O ponto de presença do Azure, geralmente abreviado como PoP, é um ponto de acesso ou uma localização física na qual o tráfego pode entrar ou sair da rede global da Microsoft.

## Referência
https://azure.microsoft.com/pt-br/explore/global-infrastructure
