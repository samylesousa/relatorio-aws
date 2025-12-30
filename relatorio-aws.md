# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

*Data: 30/12/2025
*Empresa: Abstergo Industries 
*Responsável: Samyle Sousa

## Introdução
Este relatório apresenta a proposta para o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Samyle Sousa. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (especificamente o S3 Standard)
- É uma ferramenta de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados e segurança. Além disso possui um preço baixo e uma perfomance boa.
- Para a empresa seria usado como ferramenta para armazenar notas fiscais, certificados de qualidade, bulas e relatórios de auditoria. Ou seja, dados que são acessados com frequência, o que também é um dos focos do S3 Standard.

Etapa 2: 
- Lambda e EventBridge
- São duas ferramentas diferentes. O Lambda é um serviço de computação que executa código sem a necessidade de gerenciar servidores, sendo o código executado automaticamente, com preços baseados apenas no uso. Por sua vez, o EventBridge é um serviço sem servidor que usa eventos para conectar componentes da aplicação, possuindo uma arquitetura voltada para eventos que aumenta a agilidade, confiabilidade e escalabilidade.
- A empresa poderia utilizar essas duas ferramentas em conjunto para um sistema de alerta de vencimento de medicamentos, no qual o EventBridge dispararia todo dia em determinado horário consultas para o banco de dados (as quais verificariam os medicamentos que iriam vencer em X dias) e então depois seria gerado um relatório que por fim seria enviado por email para os gerentes. 

Etapa 3: 
- Amazon Quick Suite
- É uma plataforma generativa de inteligência de negócios que facilita a análise de dados, criação de visualizações, automação de fluxos de trabalho e a colaboração em toda a organização. É uma ferramenta que combina recursos tradicionais com IA moderna.
- A principal aplicação que esse serviço iria ter na empresa seria para a criação de dashboards, que analisariam o estoque, a logística e a performance de clientes. Os dashboards seriam apresentados mensalmente para os gerentes.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado automatizar tarefas, aperfeiçoar a análise das vendas e garantir a segurança e escalabilidade dos dados*, o que aumentará a eficiência e a produtividade da empresa. Visto que, por exemplo, os prejuízos causados por medicamentos vencidos seriam evitados com a primeira proposta. Recomenda-se a a utilização das ferramentas citadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos e links úteis

* [Amazon S3](https://aws.amazon.com/pt/s3/)
* [Amazon Lambda](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/welcome.html)
* [Amazon EventBridge](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-what-is.html)
* [Amazon Quick Suite](https://docs.aws.amazon.com/pt_br/quicksuite/latest/userguide/what-is.html)

Assinatura do Responsável pelo Projeto:
Samyle Sousa
