
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: [22/05/2025]  
Empresa: Abstergo Industries    
Responsável: Diogo Vaz de Chaves    

## INTRODUÇÃO
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Diogo Vaz de Chaves. O objetivo do projeto foi "Elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos".

## Descrição do projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. À seguir, serão descritas as etapas do projeto:

Etapa 1:
- Amazon DynamoDB]

- Foco da Ferramenta: 
    . Automação de controle de estoque
    . Alta performance com baixa latência

- Descrição de caso de uso:
    . Gerenciar entradas, saídas, níveis de estoque e           movimentações de forma automatizada.
    . Reagir a eventos como vendas ou reabastecimento usando AWS Lambda.
    . Respostas em milissegundos mesmo com grandes volumes de dados, ideal para apps que precisam de agilidade no acesso ao estoque.

Etapa 2:
- AWS Identity and Access Management (IAM)

- Foco da Ferramenta: 
    . Gerenciar identidades (usuários, grupos, funções) na AWS
    . Controlar permissões com políticas que definem o que cada   identidade pode ou não fazer
    . Aplicar segurança de acesso rigorosa com autenticação multifator (MFA), segregação de funções e controle detalhado

- Descrição de caso de uso:
    . Controle de Acesso por Função (Least Privilege)
    . IAM Roles para Serviços (Lambda, EC2, API Gateway)
    . MFA (Autenticação Multifator) para Usuários
    . Políticas de Acesso Granular (Custom Policies)

Etapa 3:
- Amazon S3

- Foco da Ferramenta: 
    . Armazenar e acessar qualquer quantidade de dados a qualquer momento, de qualquer lugar, com alta disponibilidade e integração com outros serviços da AWS.

- Descrição de caso de uso:
    . Armazenamento de Relatórios de Estoque e Logs
    . Backup Automático de Dados
    . Armazenamento de Arquivos Estáticos do App ou Sistema
    . Integração com Lambda e outros serviços
    . Gerenciamento de Dados Antigos com Classes de Armazenamento
    . Armazenamento de Integrações e Exportações

## Conclusão
Foram implementados três serviços AWS — DynamoDB, IAM e S3 — com foco principal em reduzir custos para a Abstergo Industries, sem comprometer segurança e eficiência. O DynamoDB automatiza o estoque com alta performance, o IAM controla acessos de forma segura, e o S3 oferece armazenamento econômico. Essas soluções garantem uma infraestrutura mais eficiente e econômica para a empresa.


## Anexo
Política IAM - Exemplo

Configuração Bucket S3 - Regras de Lifecycle

Código Lambda - Atualização de Estoque

## Assinatura do Responsável pelo Projeto:
Diogo Vaz de Chaves
