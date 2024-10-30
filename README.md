# Criando máquinas Virtuais na Azure
# Alguns conceito abordados e revisados no tópico:
1. **Computação em Nuvem**: Refere-se ao fornecimento de recursos de TI (como armazenamento e processamento) pela internet, promovendo acesso remoto, escalabilidade e economia de custos.

2. **Modelos de Nuvem**:
   - **Nuvem Pública**: Recursos compartilhados por múltiplos usuários, com menos controle de segurança.
   - **Nuvem Privada**: Exclusiva para uma organização, oferecendo maior controle e segurança.
   - **Nuvem Híbrida**: Combina nuvens públicas e privadas para maior flexibilidade.

3. **Modelo Baseado no Consumo**: O usuário paga apenas pelo uso real de recursos, ajustando a capacidade conforme a demanda.

4. **Modelos de Preço na Nuvem**: Incluem pagamento por uso, assinatura fixa e descontos para uso contínuo, permitindo flexibilidade no custo conforme as necessidades do usuário.

No Microsoft Azure, é possível criar máquinas virtuais para executar aplicativos e serviços em um ambiente seguro, escalável e customizável. O processo começa escolhendo o sistema operacional, seja Windows ou Linux, seguido pela imagem da VM. A partir de uma imagem pré-configurada e especializada, é possível escolher uma já configurada para situações específicas, como servidores de aplicativos e bancos de dados. O tipo e o tamanho da VM são a segunda decisão. O Azure possui várias famílias de VMs, incluindo aquelas para uso geral, aquelas otimizadas para memória ou para processamento intensivo. O tamanho da VM, definido na criação pelo número de núcleos, memória e armazenamento, é a principal forma de controle de custos e desempenho. Cada VM é configurada em uma Rede Virtual, e endereços IP e regras de firewall são configuráveis para proteção da máquina. É possível adicionar identidades gerenciadas e permissões de acesso para controle do acesso seguro à VM. É possível acessar armazenamento para adicionar discos gerenciados SSD ou HDD conforme necessário. Os conjuntos de escala e disponibilidade são configuráveis para escalar a VM automaticamente ou distribuir recursos em diferentes regiões para proteção. A configuração automática é possível por Azure CLI, PowerShell. Os templates ARM replicam configurações. O monitor do Azure e o Application Manager permitem monitoramento configuração de alerta e control de vm situations contínuo. O modelo preço é baseado no uso da VM, cobrando por uso ativo e por uso de recursos configuráveis. Há opções de preços reservados com descontos para compromissos a longo prazo. Com essas etapas, o Azure permite criar VMs conforme as necessidades possíveis de cada projeto, facilitadas pela escalabilidade e controle de custos em um ambiente controlado.

