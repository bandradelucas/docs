# Kubernetes

## Serviço

Amazon EKS (Amazon Elastic Kubernetes Service)

## Destaques

- segurança
- confiabilidade
- escalabilidade

## Quem usa?

- Intel
- Snap
- Intuit
- GoDaddy
- Autodesk

## Aplicação

Pode ser usado em:

- AWS **EC2** (Amazon Elastic Compute Cloud)
- AWS **Fargate**

## AWS Fargate

Computação sem servidor para contêineres

O Fargate elimina a necessidade de provisionar e gerenciar servidores, permite que você especifique e pague pelos recursos por aplicativo, além de aumentar a segurança ao conceber aplicativos isolados
<!-- O AWS Fargate é um mecanismo de computação sem servidor para contêineres que funciona com o Amazon Elastic Container Service (ECS) e com o Amazon Elastic Kubernetes Service (EKS). O Fargate facilita a sua concentração no desenvolvimento de aplicativos. O Fargate elimina a necessidade de provisionar e gerenciar servidores, permite que você especifique e pague pelos recursos por aplicativo, além de aumentar a segurança ao conceber aplicativos isolados.
O Fargate aloca a quantidade certa de computação, eliminando a necessidade de escolher instâncias e ajustar a escala da capacidade do cluster. Você só paga pelos recursos exigidos para a execução dos contêineres, por isso não há excesso de provisionamento nem pagamento por servidores adicionais. O Fargate executa cada tarefa ou pod no próprio kernel do serviço, disponibilizando às tarefas e aos pods ambientes próprios isolados de computação. Isso permite que o aplicativo seja concebido para oferecer isolamento da carga de trabalho e segurança otimizada. É por isso que clientes, como Vanguard, Accenture, Foursquare e Ancestry, escolheram executar aplicativos de missão crítica no Fargate. -->

### Como funciona?

![Amazon Aurora](../../assets/images/aws-fargate.png)

## Amazon CloudWatch

Capacidade de observação dos seus recursos da AWS e aplicativos na AWS e no local

<!-- O Amazon CloudWatch é um serviço de monitoramento e observação criado para engenheiros de DevOps, desenvolvedores, Site Reliability Engineers (SREs – Engenheiros de confiabilidade de sites) e gerentes de TI. O CloudWatch fornece dados e insights práticos para monitorar aplicativos, responder às alterações de performance em todo o sistema, otimizar a utilização de recursos e obter uma visualização unificada da integridade operacional. O CloudWatch coleta dados de monitoramento e operações na forma de logs, métricas e eventos, oferecendo uma visualização unificada dos recursos, dos aplicativos e dos serviços da AWS executados na AWS e em servidores locais. Você pode usar o CloudWatch para detectar comportamento anômalo em seus ambientes, definir alarmes, visualizar logs e métricas lado a lado, executar ações automatizadas, resolver problemas e descobrir insights para manter seus aplicativos
em perfeita execução. -->

### Como funciona?

![Amazon Aurora](../../assets/images/aws-cloudwatch.png)

## AWS Identity and Access Management (IAM)

Gerencie com segurança o acesso aos serviços e recursos da AWS.

<!-- O AWS Identity and Access Management (IAM) permite que você gerencie com segurança o acesso aos serviços e recursos da AWS. Usando o IAM, você pode criar e gerenciar usuários e grupos da AWS e usar permissões para conceder e negar acesso a recursos da AWS.

O IAM é um recurso de sua conta da AWS disponibilizado gratuitamente. Você será cobrado somente pelo uso de outros serviços da AWS utilizados pelos usuários.

Para começar a usar o IAM, ou caso já esteja registrado na AWS, acesse o Console de Gerenciamento da AWS e obtenha conceitos básicos com estas melhores práticas do IAM.  -->

## Amazon Virtual Private Cloud

Provisione uma seção da nuvem AWS logicamente isolada na qual é possível executar recursos da AWS em uma rede virtual que você mesmo define

<!-- A Amazon Virtual Private Cloud (Amazon VPC) permite provisionar uma seção da Nuvem AWS isolada logicamente na qual é possível executar recursos da AWS em uma rede virtual que você mesmo define. Você tem controle total sobre seu ambiente de redes virtuais, incluindo a seleção do seu próprio intervalo de endereços IP, a criação de sub-redes e a configuração de tabelas de rotas e gateways de rede. Você pode usar IPv4 e IPv6 na VPC para acessar recursos e aplicativos com segurança e facilidade.
É possível personalizar facilmente a configuração da rede da Amazon VPC. Por exemplo, você pode criar uma sub-rede voltada ao público para seus servidores Web que têm acesso à Internet. Você também pode colocar seus sistemas back-end, como bancos de dados ou servidores de aplicativos, em uma sub-rede privada, sem acesso à Internet. Você pode usar várias camadas de segurança, incluindo grupos de segurança e listas de controle de acesso à rede, para ajudar a controlar o acesso às instâncias do Amazon EC2 em cada subrede. -->
