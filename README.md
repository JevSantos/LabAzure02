# Criando Máquinas Virtuais no Azure
## Resumo sobre criação de máquinas virtuais.


 A criação de máquinas virtuais (VMs) no Azure é um processo essencial para empresas que buscam escalabilidade, flexibilidade e otimização de custos nas operações de TI.

 No Azure existem diferentes Service Level Agreements (SLA), que garantem um percentual de disponibilidade VMs. Os níveis variam entre 99% a 99,999% de disponibilidade, dependendo da configuração escolhida. A escolha do nível de SLA correto é crucial para balancear custo e disponibilidade, especialmente para aplicações críticas.
 Para melhorar o SLA, é possível adotar estratégias como:
 Availability Sets protegem contra falhas de hardware, dividindo VMs em domínios de atualização e falha.
 Availability Zones distribuem VMs entre diferentes datacenters dentro de uma região, garantindo maior resiliência.
 Scale Sets aumentam a resiliência ao escalar horizontalmente as VMs.
 Na Página de Criação de Máquinas Virtuais, durante o processo de criação de uma VM, existem várias configurações, como:
 Nome da Máquina Virtual e região. A escolha da região pode impactar tanto o desempenho quanto o custo.
 Tipo de Imagem, tamanho da VM, configurações de rede, além das opções de disponibilidade.
 As contas de armazenamento e opções LRS, GRS, ZRS e GZRS do Azure fornece variações de redundância de armazenamento, que afetam tanto a resiliência dos dados quanto os custos.
 Gerenciar o custo é essencial para a utilização eficaz das máquinas virtuais no Azure.
 Para monitorar e otimizar, utiliza-se ferramentas como Azure Cost Management para rastrear e otimizar gastos e receber recomendaçoes de tamanhos mais econômicos de VMs.
 Criar de máquinas virtuais no Azure é um processo altamente configurável que permite alinhar desempenho, disponibilidade e custo às necessidades de cada aplicação.  A escolha correta das estratégias de disponibilidade e armazenamento, além de otimizar custos com instâncias reservadas e spot VMs, pode trazer grande eficiência operacional para sua infraestrutura na nuvem.
