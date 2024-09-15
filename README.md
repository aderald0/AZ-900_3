# AZ-900_3
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Configurar uma instância de banco de dados no Microsoft Azure é um processo simples e flexível, permitindo hospedar bancos de dados na nuvem com alta disponibilidade, escalabilidade e segurança. Aqui está um resumo do processo:

1. Acesso ao Portal Azure
Entre no Portal Azure (portal.azure.com) com uma conta ativa.
2. Escolher o Tipo de Banco de Dados
No painel, clique em "Criar um recurso" e selecione a opção Banco de Dados.
Escolha o tipo de banco de dados que deseja criar, como:
Azure SQL Database (SQL Server)
Azure Database for MySQL
Azure Database for PostgreSQL
Cosmos DB (NoSQL)
3. Configuração Básica
Defina o nome do banco de dados.
Escolha a assinatura e o grupo de recursos onde o banco será criado.
Selecione a região onde a instância será hospedada.
Para serviços como SQL Database, defina o tipo de computação e armazenamento (vCore ou DTU), que determinam o poder de processamento e o desempenho.
4. Autenticação e Segurança
Configure o método de autenticação, como usuário e senha ou Azure Active Directory (AAD).
Defina as regras de firewall para permitir o acesso externo ao banco de dados, como endereços IP autorizados.
5. Configurações Avançadas
Configure backup e replicação para garantir alta disponibilidade e recuperação de dados.
Defina a camada de preço e o desempenho (escolha entre camadas Básica, Standard ou Premium).
Habilite o georreplicação para alta disponibilidade em várias regiões.
6. Revisão e Criação
Revise todas as configurações, verifique o custo estimado e clique em "Criar" para provisionar a instância de banco de dados.
7. Gerenciamento
Depois de criada, você pode gerenciar a instância via Azure Portal, usar o Azure CLI ou conectar-se com ferramentas de gerenciamento de banco de dados (como o SQL Server Management Studio ou MySQL Workbench).
Benefícios
Escalabilidade Automática: Aumente ou diminua o poder de computação conforme a necessidade.
Alta Disponibilidade: Com suporte a replicação e failover automático, garantindo continuidade em caso de falhas.
Segurança: O Azure oferece criptografia de dados em repouso e em trânsito, além de controle de acesso detalhado.
Este processo permite criar e gerenciar bancos de dados de forma eficiente, com opções de automação e integração com outros serviços Azure.
