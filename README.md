# RELATÓTIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 24/02/2026
Empresa: Abstergo Industries 
Responsável: Wesley Bueno

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Wesley Bueno. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especi­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3
- O Amazon S3 é um serviço de armazenamento de objetos que oferece durabilidade e escalabilidade virtualmente infinitas, ideal para guardar dados que precisam perdurar por anos para análises ou conformidade. Ele possui um mecanismo de otimização de custos baseado na frequência de acesso aos arquivos; basta selecionar a classe de armazenamento que mais fizer sentido, seja para dados acessados frequentemente ou para arquivos de arquivamento de longo prazo.
- Podemos usar os buckets do Amazon S3 para substituir nossos sistemas de backup em fita e storages físicos, garantindo maior durabilidade a um custo menor. Além disso, ele servirá como um repositório central para dados utilizados por diversas aplicações, garantindo acesso rápido e seguro, sem gerar concorrência ou custos de consulta em nosso banco de dados principal.

Etapa 2: 
- Amazon RDS
- O RDS (Relational Database Service) é um serviço de banco de dados relacional gerenciado pela AWS que facilita a configuração, operação e o dimensionamento na nuvem. A AWS gerencia todas as tarefas administrativas complexas, como atualizações, backups e provisionamento de hardware, o que permite que nossa equipe foque inteiramente na construção das aplicações e na análise dos dados.
- Com esta implementação, eliminamos a necessidade de um datacenter físico para bancos de dados, cortando drasticamente os gastos com compra de equipamento, manutenção, segurança e refrigeração. A redução de custo será significativa, pois pagaremos apenas pelos recursos que utilizarmos na nuvem, com a vantagem de ter backups automáticos e gerenciamento simplificado. Podemos mover toda a operação de dados para a nuvem para monitorar vendas e recursos da empresa através de KPIs e dashboards.

Etapa 3: 
- EC2
- O EC2 (Elastic Compute Cloud) é um serviço que fornece capacidade computacional segura e redimensionável na nuvem, na forma de servidores virtuais. As máquinas podem ser configuradas conforme a necessidade de cada aplicação e acessadas remotamente pelos colaboradores. A manutenção física e a segurança dos equipamentos são gerenciadas pela Amazon, e o modelo de cobrança é baseado no uso.
- Com a implementação do EC2, podemos escalar nossas aplicações para serem executadas em ambientes virtuais, economizando em infraestrutura física. Podemos configurar as máquinas para serem executadas somente quando necessário (ex: em horário comercial), aumentando ainda mais a redução de custos. A segurança e a continuidade dos negócios são aprimoradas pela capacidade de manter cópias das aplicações em mais de uma região para recuperação em caso de problemas.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado uma otimização de custos diretos com infraestrutura e operações. Além da economia, a empresa ganhará em agilidade para desenvolver novos projetos, segurança para seus dados críticos e escalabilidade para suportar o crescimento futuro, o que aumentará¡ a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- https://aws.amazon.com/pt/?nc2=h_home
- https://aws.amazon.com/pt/ec2/instance-types/
- https://aws.amazon.com/pt/s3/?nc2=h_ql_prod_fs_s3
- https://aws.amazon.com/pt/rds/?nc2=type_a

Assinatura do Responsável pelo Projeto: 

Wesley Bueno
