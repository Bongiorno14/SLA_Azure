# VARIAÇÕES DE DISPONIBLIDADE SLA
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Bongiorno14/SLA_Azure/blob/main/LICENSE) 

# Sobre o projeto

Consiste na verificação dos rates de SLA disponibilizados atualmente na Azure (Mar/24), bem como exemplos práticos de utilizaçao para cada uma deles.\

É um projeto muito simples, mas de suma importancia, pois se durante o processo de desenvolvimento de um projeto náo efetuarmos a escolha adequada para a nossa necessidade, poderemos estar com um sistema que náo nos atenda ou talvez até pagando um valor muito mais alto, sem ter a real necessidade.

Permaneço a disposiçao para maiores esclarecimentos e principalmente para receber críticas e sugestões da forma que venho conduzindo estes repositórios.

# Descriçao dos percentuais e exemplos práticos de utilização.

O Azure oferece vários SLAs (Service Level Agreements) para seus serviços, garantindo níveis específicos de disponibilidade e desempenho. Aqui estão alguns dos principais SLAs do Azure e exemplos de aplicações para cada percentual:

## 99,9% de disponibilidade:
- Serviço de Máquinas Virtuais (VMs): Ideal para aplicações web, bancos de dados e aplicativos empresariais que exigem alta disponibilidade.
- Exemplo prático: Uma aplicação web de comércio eletrônico hospedada em Máquinas Virtuais do Azure. Nesse caso, a disponibilidade de 99,9% garantiria que o site estivesse operacional e acessível para os usuários praticamente o tempo todo, exceto por curtos períodos de manutenção planejada.

## 99,95% de disponibilidade:
- Azure SQL Database: Aplicativos críticos que requerem um banco de dados relacional altamente disponível e escalável.
- Exemplo prático: Um aplicativo de gerenciamento de documentos que armazena arquivos no Azure Blob Storage. Com uma disponibilidade de 99,95%, os usuários teriam acesso constante aos seus documentos sem interrupções significativas, permitindo um fluxo de trabalho consistente e confiável.
  
## 99,99% de disponibilidade:
- Azure Cosmos DB: Aplicativos globais, IoT e aplicações que exigem baixa latência e alta disponibilidade em todo o mundo.
- Azure Kubernetes Service (AKS): Para implantação de contêineres e orquestração de aplicativos em escala, garantindo alta disponibilidade e dimensionamento automático.
- Exemplo prático: Um sistema de registro e análise de dados em tempo real usando Azure Cosmos DB. Com essa disponibilidade elevada, o sistema seria capaz de lidar com picos de tráfego e garantir acesso aos dados em várias regiões do mundo com uma latência mínima, mesmo em circunstâncias adversas.
  
## 99,999% de disponibilidade (também conhecido como "Cinco Nove" ou "Five Nines"):
- Azure Active Directory (AD): Importante para autenticação e controle de acesso em larga escala, garantindo alta disponibilidade para serviços e aplicativos.
- Azure Traffic Manager: Para distribuição de tráfego global entre várias instâncias de aplicativos em diferentes regiões, garantindo alta disponibilidade e desempenho otimizado.
- Exemplo prático: Um ambiente crítico de autenticação e gerenciamento de identidade usando Azure Active Directory. Com essa alta disponibilidade, o serviço de autenticação estaria praticamente sempre disponível, garantindo que os usuários possam acessar os sistemas e recursos corporativos sem interrupções significativas.
  
# Aprendizado

3 Pontos importantes para a escolha do SLA.
- Entendimento da Disponibilidade Requerida: A utilização da SLA (Service Level Agreement) começa com a compreensão das necessidades de disponibilidade da aplicação ou serviço. 
- Escolha do Nível de SLA Adequado: Com base nas exigências de disponibilidade, é crucial escolher o nível de SLA apropriado oferecido pelo provedor de serviços, avaliando os custos associados a cada nível.
- Implementação e Monitoramento Contínuo: Após selecionar o nível de SLA adequado, é essencial implementar as medidas necessárias para garantir a conformidade com os termos do acordo. 
