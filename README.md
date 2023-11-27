# Banco-de-dados-II.II
Exercicio prático


Após uma varredura rápida no sistema de banco de dados de uma empresa de vendas, identificamos a necessidade de melhorar a segurança dessas informações. Por isso, será necessário desenvolver um novo banco para armazenar os dados mais importantes, como detalhes dos clientes, valores faturados diariamente e informações sobre os produtos, além de outros. Sendo assim, explique quais são os pilares da segurança de dados que devem ser seguidos para que o novo banco seja bem projetado e funcione corretamente


Para garantir a segurança dos dados em um novo banco de dados, é importante seguir os seguintes pilares:

Confidencialidade: Garantir que o acesso aos dados seja restrito apenas às pessoas autorizadas. Isso envolve a implementação de autenticação e controle de acesso, como a utilização de senhas fortes e políticas de acesso baseadas em roles ou perfis de usuários. É importante também criptografar dados sensíveis em repouso e em trânsito.

Integridade: Assegurar que os dados permaneçam íntegros e não sofram alterações não autorizadas. Isso pode ser alcançado através do uso de técnicas como checksums, assinaturas digitais, controle de versões, validação de entradas e saídas, além de restrições e validações no nível do banco de dados.

Disponibilidade: Garantir que os dados estejam disponíveis quando necessário. Isso envolve a implementação de backups regulares, redundância de hardware e sistemas, monitoramento contínuo de problemas e contingências, bem como a implementação de políticas de recuperação de desastres.

Auditabilidade: Registrar todas as atividades relacionadas aos dados, como acesso, modificações e exclusões. Isso permite a análise de registros para detectar atividades suspeitas ou não autorizadas e fornecer uma trilha de auditoria caso seja necessário investigar possíveis violações.

Conformidade: Seguir as regulamentações e legislações aplicáveis relacionadas à segurança de dados, como a Lei Geral de Proteção de Dados (LGPD). Isso envolve a implementação de medidas técnicas e organizacionais adequadas para garantir a conformidade com os requisitos legais e assegurar a privacidade dos dados.

Além desses pilares, é importante também implementar boas práticas de segurança, como a atualização regular de software e sistemas, a remoção de acesso desnecessário aos dados, a proteção contra ataques conhecidos (como injeção de SQL e cross-site scripting), o uso de firewalls e a monitoração rigorosa dos registros e logs do sistema.

Ao seguir esses pilares e boas práticas, é possível desenvolver um banco de dados seguro que proteja adequadamente as informações da empresa e ofereça confiança aos usuários e clientes.
