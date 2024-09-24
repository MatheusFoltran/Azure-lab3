# Configurando uma instância de Banco de Dados

A configuração de uma instância de banco de dados no Azure é um processo que oferece diversas opções para atender às necessidades específicas de uma aplicação. Aqui está uma visão geral dos principais aspectos envolvidos na criação e configuração de bancos de dados na Azure:

Configurações de Armazenamento
Ao configurar um banco de dados, você pode escolher diferentes opções de armazenamento, que incluem:

Armazenamento padrão: Geralmente baseado em HDD, adequado para cargas de trabalho menos exigentes.
Armazenamento premium: Baseado em SSD, adequado para aplicações que exigem desempenho superior e latência mais baixa.
Provisionamento de IOPS: Para otimizar o desempenho do banco de dados com base nas necessidades específicas de leitura e escrita.
Autenticação
A autenticação é uma parte crucial da configuração do banco de dados. Você pode escolher entre diferentes métodos de autenticação:

Microsoft Entra ID: Permite que usuários e serviços autentiquem-se usando credenciais do Azure Active Directory, o que é especialmente útil para integrações de segurança corporativa.
Autenticação SQL: Uma forma tradicional que permite a autenticação com um nome de usuário e senha específicos do banco de dados. Essa opção é adequada para aplicações que não utilizam o Azure AD.
Redundância e Alta Disponibilidade
Para garantir que seus dados estejam sempre disponíveis e seguros, você pode configurar opções de redundância e alta disponibilidade:

Geo-redundância: A replicação de dados em diferentes regiões para proteção contra falhas regionais.
Backup automático: O Azure realiza backups automáticos do banco de dados, garantindo que você possa restaurar dados em caso de perda ou corrupção.
Zonas de Disponibilidade: Para garantir que a instância do banco de dados continue operando mesmo em caso de falhas de hardware.
Estimativa de Custos
Ao configurar o banco de dados, a Azure fornece uma estimativa de custos baseada nas seleções feitas. Esses cálculos incluem:

Recursos selecionados: Como tipo de banco de dados, opções de armazenamento e configurações de escalabilidade.
Tempo de uso: Com base no tempo que a instância do banco de dados ficará ativa.
Custo de transferência de dados: Para dados que são transferidos para fora do Azure.
Essa funcionalidade de estimativa de custos ajuda a planejar o orçamento e a entender o impacto financeiro das escolhas de configuração.
