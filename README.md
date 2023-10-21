# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 20/10/2023
Empresa: Abstergo Industries 
Responsável: Darlan Rafael Santos Machado

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Darlan Rafael Santos Machado. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 - Glacier Deep Archive
- Armazenamento de dados cujo acesso não seja frequente
- Ao utilizar esta ferramenta, será possível armazenar as receitas de medicamentos controlados e/ou antibióticos, de acordo com a legislação. Esta ferramenta é ideal para armazenar arquivos que são pouco acessados e que precisam ser mantidos por necessidades legais por períodos de 7 a 10 anos.

Etapa 2: 
- Amazon DynamoDB
- Banco de dados não relacional.
- A opção por este sistema de gerenciamento de bancos de dados seria crucial para permitir uma maior performance tanto na gravação quanto na recuperação de informações que os diversos sistemas da Abstergo Industries utiliza. Como a empresa prevê crescimento em suas operações nos próximos anos, a ferramenta já possui suporte para escalabilidade automática, bem como a replicação de dados regional. Além disso, os custos com DBAs e com a infraestrutura de bancos de dados será toda revertida para a ferramenta aqui citada.

Etapa 3: 
- Amazon Elastic Container Service - ECS
- Execução de containers
- Como a Abstergo Industries busca atualizar sua estrutura sistêmica, o primeiro passo é passar do modelo monolítico para um sistema com arquitetura de micro serviços. Para isso, é fundamental o uso de containers, visando isolar os processos e garantir maior solidez na aplicação da arquitetura. Os ganhos com a escalabilidade e alta disponibilidade superam e muito os custos que vão existir. Sem contar que o acesso às ferramentas S3 e DynamoDB tendem a ser muito mais simples e vão garantir uma estrutura robusta e adequada aos negócios e futuros planos da empresa.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos, alta disponibilidade, maior performance, maior segurança, escalabilidade, replicação regional ou multi zonas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]

Assinatura do Responsável pelo Projeto:

[Nome do Responsável pelo Projeto]

