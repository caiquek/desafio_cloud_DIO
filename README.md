1. Visão Geral do Projeto
Este projeto tem como objetivo principal a redução imediata e sustentável dos custos operacionais da infraestrutura na Amazon Web Services (AWS) da empresa [Nome da Empresa]. Focamos na implementação e utilização de três serviços/práticas essenciais da AWS que garantem maior eficiência, right-sizing dos recursos e compromisso de uso estratégico.

O projeto foi executado por [Nome do Responsável pelo Projeto].

2. Metas e Objetivos
Meta Principal: Diminuir os gastos mensais com a AWS, garantindo a performance necessária para as aplicações críticas.

Objetivos Específicos:

Implementar o dimensionamento correto (right-sizing) das instâncias computacionais.

Otimizar automaticamente os custos de armazenamento de objetos S3.

Reduzir o custo por hora de uso de recursos computacionais através de compromissos de longo prazo.

3. Serviços Implementados para Redução de Custos
O projeto foi estruturado em três frentes de ação, cada uma utilizando uma ferramenta ou serviço específico da AWS:

1. AWS Compute Optimizer (Otimização Computacional)
Foco: Garantir que as instâncias Amazon EC2 e volumes EBS não estejam superprovisionados.

Ação: O serviço analisou as métricas de utilização e forneceu recomendações para downsizing (troca por instâncias menores ou mais adequadas) de recursos com baixa utilização.

Impacto: Redução direta nos custos de computação e armazenamento.

2. Amazon S3 Intelligent-Tiering (Otimização de Armazenamento)
Foco: Otimização automática e dinâmica dos custos de armazenamento de objetos.

Ação: Configuração de buckets chave para que o Intelligent-Tiering monitore os padrões de acesso e mova automaticamente os dados não acessados para uma camada de armazenamento mais barata (Acesso Infrequente).

Impacto: Elimina a necessidade de gerenciamento manual do ciclo de vida dos dados e minimiza os custos de armazenamento de dados "frios".

3. Savings Plans (Compromisso de Uso)
Foco: Redução de custos em troca de um compromisso de uso contínuo de recursos.

Ação: Análise do uso histórico de EC2 e Fargate/Lambda e aquisição de um Compute Savings Plan para um período de 1 ou 3 anos.

Impacto: Desconto imediato e significativo (até 66%) na fatura, aplicado automaticamente em todo o uso de computação elegível, proporcionando previsibilidade e grande economia.

4. Resultados Esperados
A implementação bem-sucedida dessas três estratégias deve resultar em:

Redução imediata nos custos de EC2, EBS e S3.

Maior eficiência e melhor alocação de recursos.

Melhor previsibilidade de gastos com o compromisso do Savings Plan.

5. Próximos Passos e Continuidade
Monitorar o painel do AWS Cost Explorer para validar as economias pós-implementação.

Revisar periodicamente as recomendações do Compute Optimizer para otimizações contínuas.

Explorar novas oportunidades de economia (ex: migração para instâncias Graviton, otimização de serviços de banco de dados).
