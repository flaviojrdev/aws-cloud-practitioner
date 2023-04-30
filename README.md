# 📓 Informações da Prova

| Domínio                  | % do exame |
|--------------------------|------------|
| Conceitos de nuvem       | 26%        |
| Segurança e conformidade | 25%        |
| Tecnologia               | 33%        |
| Faturamento e preços     | 16%        |
| **TOTAL**                | **100%**   |

**Tempo da prova**: 90 minutos (Podendo solicitar mais 30 minutos caso faça em língua estrangeira).

**Questões não pontuadas**: 15 das 65 questões são apenas questões testes para ajudar a melhorar provas futuras e não contabilizam pontos.

**Acertos mínimos**: 70% (35 das 50 questões pontuadas).

# ☁ Conceitos gerais de cloud

### Computação em Nuvem (Cloud Computing)

A pratica de usar uma rede de servidores remotos hospedados na internet para armazenar, gerenciar e processar dados, ao invés de um servidor local ou computador pessoal.

### On-Premise VS Cloud

| On-Premise (Servidores Locais) | Cloud Computing (Servidores na Nuvem) |
|--------------------------------|---------------------------------------|
| Você mantém os servidores.     | O provedor é responsável pela infraestrutura física. |
| Você contrata e gerencia a equipe de infraestrutura física. | O provedor contrata e gerencia a equipe de infraestrutura física. |
| Pagamento ou aluguel de equipamentos. | O provedor paga pelos equipamentos e manutenção. |
| Você assume os riscos físicos. | Você configura o código e serviços, o provedor assume os riscos físicos |

### Vantagens da cloud

#### Nova documentação

- Agilidade
- Pay-as-you-go (pague o que usar)
  - Troca de capital expense (gastos com infraestrutura de TI) por variable expense (gastos variáveis com serviços em nuvem)
- Economy of scale (economia de escala)
  - Você está dividindo os custos do servidor com outros clientes
  - Centena de milhares de clientes utilizando uma fração do servidor
- Infraestrutura global
- Segurança
- Confiabilidade
- Alta disponibilidade
- Elasticidade

#### Antiga documentação

- Trade capital expense for variable expense
- Benefit from massive economies of scale
- Stop guessing capacity
- Increase speed and agility
- Stop spending money on running and maintaining data center
- Go global in minutes

### Tipos de serviços cloud

- **IaaS**: Infraestrutura como serviço
  - Computação
  - Rede
  - Banco de Dados
  - Armazenamento
- **PaaS**: Plataforma como Serviço
  - Ambiente de desenvolvimento
  - Ferramentas de suporte
  - Bibliotecas de código
- **SaaS**: Software como Serviço
  - Aplicações completas
  - Modelos de assinatura

### Modelos de implantação de nuvem (Deployment Models)

- Público
  - Tudo é construído no provedor cloud.
- Privado
  - Tudo é construído no datacenter da empresa (On-Premise).
- Híbrido
  - Usa ambos On-Premsise e provedor cloud.
- Cross-Cloud
  - Usa múltiplos provedores cloud.

# 👨‍💻 Conceitos gerais da AWS

### Infraestrutura Global

A AWS possui datacenters distribuídos globalmente e conectados físicamente uns aos outros para que funcione como um recurso de larga escala ao consumidor final.

**Regiões**
- Áreas geográficas para oferecer serviços em nuvem
- Possui multíplas AZs

**Zonas de Disponibilidade (AZ)**
- Um ou mais data centers fisicamente separados dentro de uma região
- Todas as AZs são interconectadas em até 100km (60 milhas)
- Próximas o suficiente para ter uma baixa latência
- Longe o suficiente para evitar que desastres naturais afetem a disponibilidade
- Uma região geralmente contém 3 AZs
- É uma boa prática executar carga de trabalho nas 3 AZs para garantir alta disponibilidade
- São representados pelo código da região seguido de uma letra. Exemplo: us-east-1**a**
- Associadas a uma subnet

**Direct Connection Locations**
- Locais de interconexão de rede direta.
  
**Points of Presence (PoP)**
- Pontos de presença para distribuir conteúdo em todo o mundo
- É um datacenter que pertence a AWS ou um parceiro
- Pode ser um Edge Location ou Regional Edge Caches
  
**Local Zone**
- Extensão de uma região para infraestrutura em nuvem de baixa latência
  
**Wavelenght Zones**
- Zonas de disponibilidade para conectividade ultrarrápida

**Edge Locations**
- Permitem o armazenamento em cache de conteúdo e a entrega de serviços com baixa latência aos usuários finais

**AWS Outposts**
- Servidores físicos que podem ser colocados no data center, seus dados vão residenter onde o outposts estiver

### Modelo de responsabilidade compartilhada

- O cliente é responsável pela segurança **na** nuvem e a AWS a segurança e infraestrutura **da** nuvem.
- A AWS protege o data center, enquanto o cliente protege as aplicações.

### AWS Well-Architected Framework (6 pilares): Melhores Práticas

**Excelência Operacional**: Execução e monitoramento sistemas e melhoria contínua de processos e procedimentos.
- Performar operações como código.
- Mudanças frequentes, pequenas e reversíveis.
- Refinar processos operacionais frequentemente.
- Antecipar falhas.
- Aprender com as falhas operacionais.

**Segurança**
- Implementar fundamentos de segurança sólidos.
- Habilitar rastreamento.
- Aplicar segurança em todas as camadas.
- Automatizar melhores práticas de segurança.
- Proteger dados em trânsito e parados.
- Manter pessoas longe dos dados.
- Preparar-se para eventos de segurança.

**Confiabilidade**

**Eficiência de Desempenho**

**Otimização de Custos**

**Sustentabilidade**

# 🔧 Ferramentas de Gerenciamento e Desenvolvimento

### AWS Command Line Interface (CLI)

- Permite interagir com a API AWS via comandos no shell
- É um programa executável em Python (logo requer o Python instalado)

### AWS Software Development Kit (SDK)

- É uma coleção de ferramentas de desenvolvimento em um único pacote instalável
- Oferecido em diversas linguagens

### AWS CloudShell

- É um shell baseado em navegador implementado no console de gerenciamento da AWS
- Escopo por região (1GB de armazenamento grátis por região)

# ⚙ Serviços da AWS

### 📊 Análises

**Athena**

**Kinesis**

**QuickSight**

<hr>

### 📩 Integração de aplicações

**SNS (Simple Notification Service)**

**SQS (Simple Queue Service)**

<hr>

### 🔑 Autenticação e Autorização

**IAM (Identity and Access Management)**

**Cognito**

<hr>

### 🖥 Computação & Serverless

**EC2 (Elastic Computing 2)**
- Serviço de servidores virtuais

**Batch**

**Elastic Beanstalk**

**Lambda**

**Lightsail**

**Workspaces**

<hr>

### 📦 Contêineres

**ECS (Elastic Container Service)**

**EKS (Amazon Elastic Kubernetes Service**

**Fargate**

<hr>

### 🛢 Banco de Dados

**Aurora**

**DynamoDB**

**RDS (Relational Database Service)**

**Redshift**

<hr>

### 🛠 Ferramentas de Desenvolvedor

**CodeBuild**

**CodeCommit**

**CodeDeploy**

**CodePipeline**

**CodeStar**

<hr>

### 👥 Interação com os Clientes

**Amazon Connect**

<hr>

### 🔍 Gerenciamento, Monitoramento e Governança

**Auto Scaling**
- ASG (Auto Scaling Groups): Automaticamente remove ou adiciona servidores baseado nas regras de escalonamento que você define baseado em métricas

**Budgets**

**CloudFormation**

**CloudTrail**

**CloudWatch**

**AWS Config**
- Serviço de políticas/regras como códigos. Você pode criar regras para verificar as configurações dos seus recursos, caso desviem do estipulado você será alertado ou em alguns casos será auto remediado.

**Relatório de Custos e Uso da AWS**

**EventBridge (CloudWatch Events)**

**License Manager**

**Managed Services**

**Organizations**

**Secrets Manager**

**Systems Manager**

**Systems Manager Parameter Store**

**Trusted Advisor**

<hr>

### 🌐 Redes e Entrega de Conteúdo

**API Gateway**

**CloudFront**
- CDN (Content Delivery Network) ou serviço de entrega de conteúdo
- Roteia requisições aos Edge Locations mais próximos

**Direct Connect**
- Conexão direta/privada do seu datacenter com a AWS
- Possui Direct Connect Locations que são datacenter de parceiros 

**VPC (Virtual Private Cloud)**

<hr>

### 🛡 Segurança, Identidade e Conformidade

**Artifact**

**ACM (AWS Certificate Manager)**

**CloudHSM**

**Cognito**

**Detective**

**GuardDuty**

**IAM (Identity and Acess Management)**

**Inspector**

**License Manager**

**Macie**

**Shield**

**WAF**

<hr>

### 🗃 Armazenamento

**AWS Backup**

**EBS (Elastic Block Store)**

**EFS (Elastic File System)**

**S3 (Simple Storage Service)**

**S3 Glacier**

**Snowball Edge**

**Storage Gateway**
