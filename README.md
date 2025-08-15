# Resumo-do-Lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO para o Bootcamp: Microsoft 50 anos - Computação em Nuvem com a Azure

# O que é Computação em Nuvem?
A Computação em Nuvem é um modelo que oferece serviços de infraestrutura, armazenamento e processamento de dados pela internet, eliminando a necessidade de servidores e data centers locais. Nesse modelo, empresas e usuários:
- Evitam custos com infraestrutura física
- Acessam recursos sob demanda, pagando apenas pelo que utilizam
- Beneficiam-se de escalabilidade, flexibilidade e agilidade.
Os principais tipos de nuvem são: pública, privada e híbrida.

### Infraestrutura
Conjunto de recursos físicos ou virtuais necessários para operar sistemas de TI, como:
- Redes
- Armazenamento
- Servidores

#### Modelos de infraestrutura
On-Premise (local): Infraestrutura física gerenciada pela empresa em data centers locais.
- Vantagens: Controle total
- Desvantagens: Alto custo inicial e manutenção

Cloud: Serviços terceirizados via internet
- Vantagens: Escalabilidade, redução de custos
- Desvantagens: Dependência do provedor

Híbrido: Combina recursos locais e na nuvem
- Vantagens: Flexibilidade para migração gradual
- Desvantagens: Complexidade de gerenciamento

### CapEX Vs. OpEX
CapEX: Gastos com ativos de longo prazo (infraestrutura). Ex.(Compra de servidores para data center).
OpEX: Gastos operacionais recorrentes (pagamento conforme o uso). Ex.(Assinatura mensal do Azure).
#### Diferença chave:
o CapEX é o investimento inicial alto e depreciável ao tempo, enquanto o OpEX são os custos contínuos, mas sem gastos upfront (antecipados).

### Benefícios da Nuvem
- Alta disponibilidade: Serviços acessíveis 24/7
- Escalabilidade: Ajuste de recursos conforme demanda
- Segurança: Proteção gerenciada por especialistas.
- Elasticidade: Expansão ou redução automática de recursos

### Modelos de serviços em nuvem
Modelos de serviços em nuvem definem o nível de controle que a empresa tem sobre a infraestrutura e os serviços fornecidos pelo provedor de nuvem.
- IaaS (Infraestrutura como serviço): Infraestrutura (redes, VMs).
Ex.: AWS EC2, Azure VMs

- PaaS (Plataforma como serviço): Plataforma para desenvolvimento.
Ex.: Azure App Service

- SaaS (Software como serviço): Aplicativos prontos.
Ex.: Microsoft 365, Google Workspace

### Regiões e Zonas de Disponibilidade
- Regiões são áreas geográficas com data centers, como paises por exemplo.
- Zonas de disponibilidade (AZs) são data centers isolados dentro de uma região para tolerância a falhas. O objetivo dessa divisão é principalmente garantir a resiliência e baixa latência.

### Grupo de Recursos e Assinaturas no Azure
- Assinatura: Unidade de cobrança e isolamento de recursos.
- Grupo de Recursos: Contêiner lógico para organizar recursos relacionados (ex.: VMs, bancos de dados).

#### Hierarquia no Azure
A estrutura lógica do Azure segue esta ordem:
Azure AD (Diretório) --> Assinaturas --> Grupo de Recursos --> Recursos

Vantagens: Facilita gerenciamento e exclusão de recursos, também permite o controle de acesso granular (RBAC).
