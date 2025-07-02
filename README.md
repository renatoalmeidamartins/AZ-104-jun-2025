# AZ-104-jun-2025

## Meus dados:
- [Transcript Microsoft](https://learn.microsoft.com/en-us/users/renatomartins-7213/transcript/dqlr3cjep5q3r9m?source=docs)
- [Perfil no Linkedin](https://www.linkedin.com/in/renatodealmeidamartins/)

## Links gerais:
- [Repo com labs e demos](https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator)
- [Link do ambiente de lab](https://esi.learnondemand.net/Class/694157)
- [Acesso ao material do curso, via Microsoft Learn](https://learn.microsoft.com/en-us/training/courses/az-104t00?WT.mc_id=esi_m2l_content_wwl&ocid=%20#study-guide)

## Problemas com labs
Os links de download files estão quebrados nos labs. Os arquivos mencionados estão identificados abaixo:
- Lab 4, "Manage Azure Resources by using ARM templates". O arquivo [azuredeploydisk.bicep](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/03/azuredeploydisk.bicep)
- Lab 5, "Implement Virtual networking", faltam dois arquivos:
  - [az104-04-parameters.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/04/az104-04-parameters.json)
  - [az104-04-template.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/04/az104-04-template.json)
- Lab 7, "Implement network traffic management",  faltam dois arquivos:
  - [az104-06-vms-parameters.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/06/az104-06-vms-parameters.json)
  - [az104-06-vms-template.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/06/az104-06-vms-template.json)
- Lab 8, "Manage Azure Storage", falta esta imagem [az104-lab07-architecture-diagram.png](https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/blob/master/Allfiles/Labs/07/az104-lab07-architecture-diagram.png?raw=true)
- Lab 13, "Implement data protection", faltam:
  - [az104-10-vms-edge-parameters.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/10/az104-10-vms-edge-parameters.json)
  - [az104-10-vms-edge-template.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/10/az104-10-vms-edge-template.json)
- Lab 14, "Implement monitoring", falta [az104-11-vm-template.json](https://raw.githubusercontent.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/refs/heads/master/Allfiles/Labs/11/az104-11-vm-template.json)

## Links do dia 1
- ["Mapa" de serviços AWS e seus equivalentes no Azure](https://learn.microsoft.com/en-us/azure/architecture/aws-professional/)
- [Comparação entre Enra ID e Active Directory](https://learn.microsoft.com/en-us/entra/fundamentals/compare)
- [Elevando acesso de um Admin global](https://learn.microsoft.com/en-us/azure/role-based-access-control/elevate-access-global-admin?tabs=azure-portal%2Centra-audit-logs)
- [Políticas de Assinatura do Azure/Entra ID](https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/manage-azure-subscription-policy)
- [Unidades administrativas (semelhantes a OUs no ADDS) no Entra](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/administrative-units)
- [Planos e recursos do Entra ID, atenção às várias "abas", com produtos standalone e adicionais](https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing)
- [Reset de senha de auto-serviço](learn.microsoft.com/en-us/entra/identity/authentication/tutorial-enable-sspr)
- [Entra connect vs cloud sync](https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/what-is-cloud-sync)
- [Writeback (entra para AD) de dispositivos](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-connect-device-writeback)
- [Grupos dinamicos](https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership)
- [Pares de regiões](https://learn.microsoft.com/en-us/azure/reliability/regions-list)
- [Disponibilidade regional de serviços](https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/table)
- [Mapa de regiões](https://datacenters.microsoft.com/globe/explore/)
- [Serviços gratuitos e duração da gratuidade](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)
- [Cotas e limites](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits)
- [Gerenciamento centralizado de Hybrid benefit para SQL Server](https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/overview-azure-hybrid-benefit-scope)
- [Linguagem de políticas no Azure](https://learn.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure-basics)
- [Repo com exemplos de politícas, além de todas as "built-in"](https://github.com/Azure/azure-policy/tree/master)
- [Lista de roles pre-definidas do Azure](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles)
- [Lista de roles pre-definidas do Entra](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/permissions-reference)
- [Repo com os modelos de inicio rapido de ARM](https://github.com/Azure/azure-quickstart-templates/tree/master)

## Links do dia 2
- [Topologia hub and spoke de rede no centro de arquitetura](https://learn.microsoft.com/en-us/azure/architecture/networking/architecture/hub-spoke)
- [Definindo uma topologia de rede no Cloud Adoption Framework](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/define-an-azure-network-topology)
- [Acesso de saída por padrão (será desabilitado em setembro de 2025)](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/default-outbound-access#how-can-i-transition-to-an-explicit-method-of-public-connectivity-and-disable-default-outbound-access)
- [Application security groups](https://learn.microsoft.com/en-us/azure/virtual-network/application-security-groups)
- [Network service tag](https://learn.microsoft.com/en-us/azure/virtual-network/service-tags-overview)
- [Azure Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
- [Rotas de sistema e de usuário](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview)
- [Endpoints de serviço no Azure](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoints-overview)
- [Private endpoint](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview)
- [Comparativo entre service endpoint e private endpoint](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/service-endpoints-vs-private-endpoints/3962134)
- [Delegação de subnets no Azure](https://learn.microsoft.com/en-us/azure/virtual-network/subnet-delegation-overview)
- [Perfis de roteamento no traffic manager](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods)
- [Matriz de decisão dos recursos de balanceamento de carga](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/load-balancing-overview)

## Links do dia 3
- [Repo do powershell do Azure](https://github.com/Azure/azure-powershell)
- [Repo da CLI do Azure](https://github.com/Azure/azure-cli)
- [Azure Storage Explorer](https://azure.microsoft.com/en-us/products/storage/storage-explorer#Download-4)
- [Convenção de nomes de tipos de VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/vm-naming-conventions)
- [Formação do nome dos tipos de VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/overview?tabs=breakdownseries%2Cgeneralsizelist%2Ccomputesizelist%2Cmemorysizelist%2Cstoragesizelist%2Cgpusizelist%2Cfpgasizelist%2Chpcsizelist)
- [Comparativo dos recursos de Azure Bastion](https://learn.microsoft.com/en-us/azure/bastion/bastion-overview)
- [Criação de uma imagem a partir de uma VM](https://learn.microsoft.com/en-us/azure/virtual-machines/capture-image-portal)
- [Uso de compute gallery, para imagens de VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/shared-image-galleries?tabs=vmsource%2Cazure-cli)
- [Criação de VMs com o VM image builder](https://learn.microsoft.com/en-us/azure/virtual-machines/image-builder-overview?tabs=azure-powershell)
- [Usando referencia a key vault em configurações de ambiente de um App Service](https://learn.microsoft.com/en-us/azure/app-service/app-service-key-vault-references?tabs=azure-cli)
- [Extraindo informações da identidade autenticada no app service](https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-user-identities)
- [Exemplo bem simples de Dockerfile](https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/)
- [Login no Azure Container registry](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-authentication?tabs=azure-cli)
- [Não há lugar no mundo como produção](https://imwrightshardcode.com/2010/12/theres-no-place-like-production/)
- [Azure Container apps](https://learn.microsoft.com/en-us/azure/container-apps/overview)
- [Grupos de containers em Azure container Instances](https://learn.microsoft.com/en-us/azure/container-instances/container-instances-container-groups)
