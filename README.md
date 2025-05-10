#  Resumo Azure (DIO)

##  O que é o Azure
- Plataforma de **computação em nuvem pública** da Microsoft.
- Oferece serviços de: computação, banco de dados, IA, rede, etc.

---

# Modelos de Nuvem
- **Nuvem Pública**: Acessível via internet, usada por várias organizações (ex: Azure).
- **Nuvem Privada**: Infraestrutura dedicada a uma única organização.
- **Nuvem Híbrida**: Combinação de nuvens públicas e privadas.
- **Multicloud**: Uso de vários provedores de nuvem ao mesmo tempo.

---

## Benefícios do Azure
- Alta escalabilidade e disponibilidade
- Segurança e conformidade integradas
- Modelo de custo baseado em consumo (**OpEx**)
- Agilidade no provisionamento de recursos

---

## Gerenciamento de Recursos
- Utilização do **Portal do Azure**
- Conceitos importantes:
  - **Resource Group**: Agrupamento lógico de recursos
  - **Assinatura (Subscription)**: Unidade de cobrança

## Tipos de Serviços de Nuvem

A computação em nuvem oferece três principais modelos de serviço: **IaaS**, **PaaS** e **SaaS**. Cada um deles oferece diferentes níveis de controle, gestão e responsabilidade para o cliente.

 **IaaS (Infraestrutura como Serviço)**

- **O que é**: Oferece recursos de infraestrutura (máquinas virtuais, armazenamento, rede) pela nuvem.
- **Responsabilidade do Cliente**: Configuração de sistemas operacionais, aplicativos e dados.
- **Exemplo**: Amazon EC2, Microsoft Azure Virtual Machines, Google Compute Engine.
- **Vantagens**:
  - Controle total sobre a infraestrutura.
  - Escalabilidade sob demanda.
  - Economia de custos com recursos de infraestrutura.

**PaaS (Plataforma como Serviço)**

- **O que é**: Fornece uma plataforma que permite o desenvolvimento, teste e implantação de aplicativos sem gerenciar a infraestrutura.
- **Responsabilidade do Cliente**: Desenvolvimento e gerenciamento de aplicativos.
- **Exemplo**: Google App Engine, Microsoft Azure App Services, Heroku.
- **Vantagens**:
  - Não é necessário gerenciar a infraestrutura.
  - Foco no desenvolvimento de aplicativos.
  - Escalabilidade automática e facilidade de integração.

**SaaS (Software como Serviço)**

- **O que é**: Oferece software pronto para uso através da internet. O provedor gerencia toda a infraestrutura e manutenção do aplicativo.
- **Responsabilidade do Cliente**: Uso do software, sem necessidade de se preocupar com a administração.
- **Exemplo**: Google Workspace, Microsoft 365, Salesforce.
- **Vantagens**:
  - Acesso fácil e rápido a aplicativos.
  - Nenhuma responsabilidade pela manutenção ou infraestrutura.
  - Facilidade de integração com outros serviços.
 
   # Resumo: Serviços de Computação e Máquinas Virtuais do Azure

## 1. **Serviços de Computação e Máquinas Virtuais do Azure**
- **Máquinas Virtuais (VMs)** no Azure oferecem uma maneira flexível de executar sistemas operacionais e aplicativos, permitindo controle completo sobre a configuração do ambiente.
- **Tipos de Máquinas Virtuais**: VMs podem ser configuradas para diferentes tipos de carga de trabalho, como produção, testes ou desenvolvimento.
- **Escalabilidade**: Azure oferece escalabilidade automática, ajustando a quantidade de VMs conforme a demanda.

---

## 2. **Conjuntos de Disponibilidade de Máquinas Virtuais do Azure**
- **Conjuntos de Disponibilidade** ajudam a garantir a alta disponibilidade das VMs, distribuindo-as entre diferentes **domínios de falha** e **domínios de atualização**.
- Isso minimiza o risco de falhas, já que as VMs podem ser movidas entre diferentes zonas para evitar um único ponto de falha.
- **Zonas de Disponibilidade** são usadas para garantir que as VMs estejam distribuídas fisicamente em diferentes locais dentro de uma região.

---

## 3. **Área de Trabalho Virtual e Contêineres do Azure**
- **Área de Trabalho Virtual (Azure Virtual Desktop)** permite que os usuários acessem desktops e aplicativos corporativos remotos em qualquer lugar.
- **Contêineres** no Azure são leves e oferecem uma maneira de empacotar e isolar aplicativos. Azure suporta a execução de contêineres com **Azure Kubernetes Service (AKS)** e **Azure Container Instances**.

---

## 4. **Azure Functions e Serviços de Aplicativo do Azure**
- **Azure Functions** é um serviço serverless (sem servidor) que permite executar código sem precisar gerenciar a infraestrutura. Você paga apenas pelo tempo de execução do código.
- **Serviços de Aplicativo do Azure** são uma plataforma PaaS para hospedar aplicativos web e APIs, oferecendo gerenciamento automatizado de infraestrutura e escalabilidade.

---

## 5. **Computação e Rede - Revisão**
- Uma revisão dos tópicos aborda como a **computação em nuvem** oferece flexibilidade, escalabilidade e controle, enquanto os **serviços de rede** no Azure conectam e protegem recursos em nuvem e locais.


## O Language Studio no Azure AI oferece uma interface intuitiva para testar e usar a Análise de Sentimentos, permitindo que desenvolvedores e empresas implementem rapidamente essa tecnologia em suas soluções de atendimento ao cliente, monitoramento de marca ou análise de feedback.
