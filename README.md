# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21 de abril de 2024

Empresa: Abstergo Industries

Responsável: Pedro Henrique Oliveira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Henrique Oliveira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos. Como extra, elencamos mais 2 serviços visando uma melhor experiência e claridade nas explicações de redução de custo e melhoria no sistema da mesma.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 5 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Redução de custos com servidores através do Amazon EC2 Auto Scaling
- Ferramenta: Amazon EC2 Auto Scaling
- Foco da ferramenta: Escalabilidade automática de instâncias EC2
- Descrição de caso de uso: Implementação de escalabilidade automática para os servidores da empresa, permitindo que o número de instâncias EC2 seja aumentado ou reduzido automaticamente conforme a demanda. Isso reduzirá os custos operacionais, pois a empresa pagará apenas pelos recursos utilizados, evitando gastos excessivos com instâncias ociosas durante os períodos de baixa demanda.

Etapa 2: Armazenamento escalável e econômico com Amazon S3 Intelligent-Tiering
- Ferramenta: Amazon S3 Intelligent-Tiering
- Foco da ferramenta: Armazenamento de objetos escalável e econômico
- Descrição de caso de uso: Utilização do Amazon S3 Intelligent-Tiering para armazenar dados da empresa de forma escalável e econômica. Este serviço move automaticamente os dados entre os níveis de armazenamento com base no acesso dos dados, garantindo que os dados frequentemente acessados estejam armazenados no nível mais acessível e os dados menos acessados sejam movidos para um nível de armazenamento mais econômico. Isso reduzirá os custos de armazenamento da empresa, pois ela pagará menos por armazenar grandes volumes de dados.

Etapa 3: Implementação de comunicação assíncrona entre microsserviços com Amazon SQS
- Ferramenta: Amazon SQS (Simple Queue Service)
- Foco da ferramenta: Comunicação assíncrona e desacoplada entre sistemas
- Descrição de caso de uso: Utilização do Amazon SQS para implementar comunicação assíncrona entre os microsserviços da empresa. Isso permite que os sistemas enviem mensagens para as filas do SQS, que serão processadas posteriormente, desacoplando os sistemas e tornando-os mais resilientes a falhas. Além disso, o Amazon SQS é um serviço altamente escalável e cobrado com base na quantidade de mensagens processadas, o que proporcionará economia de custos à empresa, especialmente em períodos de pico de demanda.

Etapa 4: Armazenamento e gerenciamento eficiente de banco de dados com Amazon RDS
- Ferramenta: Amazon RDS (Relational Database Service)
- Foco da ferramenta: Gerenciamento de banco de dados relacional na nuvem
- Descrição de caso de uso: Utilização do Amazon RDS para armazenar e gerenciar o banco de dados relacional da empresa. O Amazon RDS simplifica tarefas como provisionamento, backup, recuperação e escalabilidade automática do banco de dados, reduzindo a carga operacional da equipe de TI e eliminando a necessidade de gerenciar infraestrutura de banco de dados, o que leva a uma redução de custos operacionais.

Etapa 5: Adição de cache para dados mais acessados com Amazon ElastiCache
- Ferramenta: Amazon ElastiCache
- Foco da ferramenta: Cache de dados em memória
- Descrição de caso de uso: Utilização do Amazon ElastiCache para adicionar uma camada de cache para os dados mais acessados pela aplicação. Isso reduzirá a latência e o custo de acesso aos dados, pois os dados frequentemente acessados serão armazenados em cache na memória, proporcionando tempos de resposta mais rápidos e reduzindo a necessidade de acessar o banco de dados principal.

## Conclusão
A implementação dessas ferramentas na empresa Abstergo Industries tem como esperado reduzir os custos operacionais, aumentando a eficiência e a escalabilidade dos sistemas. Recomendo a utilização dessas ferramentas e a exploração de novas tecnologias na AWS e melhorias no sistema interno da empresa, para que possam trazer ainda mais benefícios à empresa.

## Anexos

Para mais detalhes sobre cada tecnologia aqui abordada:

- Amazon EC2 Auto Scaling:
    Documentação: [Amazon EC2 Auto Scaling Documentation](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
    
- Amazon S3 Intelligent-Tiering:
    Documentação: [Amazon S3 Intelligent-Tiering Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html)
    
- Amazon SQS (Simple Queue Service):
    Documentação: [Amazon SQS Documentation](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
    
- Amazon RDS (Relational Database Service):
    Documentação: [Amazon RDS Documentation](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
    
- Amazon ElastiCache:
    Documentação: [Amazon ElastiCache Documentation](https://docs.aws.amazon.com/elasticache/)

Assinatura do Responsável pelo Projeto:

Pedro Henrique Oliveira
