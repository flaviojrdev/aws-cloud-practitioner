# Informações da Prova

| Domínio                  | % do exame |
|--------------------------|------------|
| Conceitos de nuvem       | 26%        |
| Segurança e conformidade | 25%        |
| Tecnologia               | 33%        |
| Faturamento e preços     | 16%        |
| **TOTAL**                | **100%**   |

- **Tempo**: 90 minutos (Podendo solicitar mais 30 minutos caso faça em língua estrangeira).
- **Acertos mínimos**: 70% (50 das 65 questões).

# Conceitos da Cloud & AWS

### ☁ Tipos de serviços cloud
- **IaaS**: Infraestrutura como serviço.
- **PaaS**: Plataforma como Serviço.
- **SaaS**: Software como Serviço.

### 🤝 Modelo de responsabilidade compartilhada
- O cliente é responsável pela segurança **na** nuvem e a AWS a segurança e infraestrutura **da** nuvem.
- A AWS protege o data center, enquanto o cliente protege as aplicações.

### 🏗 AWS Well-Architected Framework (6 pilares)

- **Excelência Operacional**:
- **Segurança**:
- **Confiabilidade**:
- **Eficiência de Desempenho**:
- **Otimização de Custos**:
- **Arquitetura**:

# Serviços da AWS

### Análises

**📊 Athena**

** Kinesis**

** QuickSight**

### Integração de aplicações

**📨 SQS (Simple Queue Service)**
- Serviço de fila de mensagens que permite o desacoplamento entre serviços.
- Permite a comunicação assíncrona entre os serviços da AWS e aplicações externas.

**📩 SNS (Simple Notification Service)**
- Serviço de envio de notificações por mensagem.
- Permite enviar mensagens por SMS, email, HTTP ou HTTPS para diferentes plataformas e aplicações.

### Autenticação e Autorização

**🔑 IAM (Identity and Access Management)**
- Serviço de gerenciamento de identidade e acesso na AWS.
- Permite criar e gerenciar usuários, grupos e permissões de acesso aos recursos.

**🔐 Cognito**
- Serviço de autenticação e autorização de usuários em aplicativos web e móveis.
- Permite criar e gerenciar usuários, grupos e tokens de autenticação.

<hr>

### Computação

**🖥 EC2 (Elastic Computing 2)**
- Serviço de servidores virtuais

**🛠 Batch**


**🚀 Elastic Beanstalk**


**⚡ Lambda**


**⛵ Lightsail**


**💼 Workspaces**

<hr>

### Armazenamento

**🪣 S3 (Simple Storage Service)**
- Armazena arquivos em forma de objetos (documento + metadado do documento)

EBS

EFS

<hr>

### Banco de dados

**🛢 RDS (Relational Database Service)**
- Banco de dados gerenciado para bancos de dados relacionais.

<hr>

### Versionamento

**🗒 CodeCommit**
- Serviço de versionamento git semelhante ao GitHub.

<hr>

### Rede

**🌐 VPC (Virtual Private Cloud)**
- Serviço de rede que permite a criação de uma rede virtual isolada na nuvem da AWS.
- Permite a criação de sub-redes, roteadores, gateways, grupos de segurança, entre outros recursos.

**👥 ELB (Elastic Load Balancing)**
- Serviço que distribui o tráfego de entrada entre várias instâncias EC2 para aumentar a escalabilidade e a disponibilidade do aplicativo.

<hr>

### Integração e Entrega Contínua (CI/CD)

**🚀 CodePipeline**
- Serviço de automação para o processo de entrega contínua.
- Permite a criação de pipelines de implantação, teste e integração.

**🛡️ CloudFormation**
- Serviço para provisionar e gerenciar recursos de infraestrutura na AWS de forma automática e consistente.
- Permite a criação de modelos de infraestrutura em formato JSON ou YAML.

<hr>

### Análise de Dados

**📈 Redshift**
- Serviço de data warehousing que permite a análise de grandes volumes de dados utilizando ferramentas de Business Intelligence (BI).



**🧮 Glue**
- Serviço de ETL (Extract, Transform and Load) totalmente gerenciado.
- Permite a integração de dados de diferentes fontes para análise e criação de relatórios. 

<hr>

### Monitoramento e Log

**🔍 CloudWatch**
- Serviço de monitoramento e observação dos recursos e aplicações da AWS.
- Permite monitorar logs, métricas, eventos, alarmes e criar dashboards personalizados.

**📜 CloudTrail**
- Serviço de registro de auditoria da AWS.
- Permite registrar todas as atividades realizadas nas contas da AWS, incluindo ações realizadas pelos usuários e pelos serviços.

**🚨 GuardDuty**
- Serviço de detecção de ameaças de segurança.
- Utiliza técnicas de machine learning para analisar eventos de várias fontes e detectar atividades maliciosas.

<hr>

### Inteligência Artificial e Machine Learning

**🤖 SageMaker**
- Serviço de machine learning totalmente gerenciado.
- Permite treinar, criar e implantar modelos de machine learning de forma rápida e fácil.

**🧠 Rekognition**
- Serviço de reconhecimento de imagem e vídeo baseado em machine learning.
- Permite identificar objetos, pessoas, texto e emoções em imagens e vídeos.

**👁‍🗨 Comprehend**
- Serviço de processamento de linguagem natural baseado em machine learning.
- Permite identificar informações importantes em texto, como sentimentos, entidades, idiomas e tópicos.

<hr>

### Mensageria


