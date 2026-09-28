Auditoria de Segurança e Conformidade - Botium Toys
🛡️ Visão Geral do Projeto
Este repositório contém uma auditoria de segurança interna simulada baseada no cenário da "Botium Toys", uma empresa fictícia de brinquedos em expansão global. O objetivo deste projeto é demonstrar habilidades práticas na avaliação de riscos, aplicação de frameworks de segurança (NIST CSF) e análise de conformidade regulatória.
Habilidades Demonstradas:
Auditoria de Segurança Interna
Avaliação de Riscos (Risk Assessment)
Análise de Conformidade (PCI-DSS, GDPR, SOC)
Framework de Segurança Cibernética do NIST (NIST CSF)
Controles de Segurança (Físicos, Técnicos e Administrativos)

📝 Relatório de Auditoria Interna
Empresa: Botium Toys Data: Setembro de 2026 Auditor(a): [Seu Nome Aqui]
1. Sumário Executivo
A Botium Toys, uma pequena empresa americana de brinquedos, experimentou um crescimento significativo em sua presença online global. Este relatório documenta a auditoria interna de TI focada em avaliar a atual postura de segurança da empresa, baseada no framework NIST CSF, para identificar vulnerabilidades e garantir a conformidade com regulamentações essenciais (PCI-DSS, GDPR e SOC).
2. Escopo da Auditoria
A auditoria abrange os ativos físicos e digitais gerenciados pelo departamento de TI, bem como os processos envolvendo armazenamento de dados, pagamentos online e adequação às leis de privacidade, com atenção especial às operações envolvendo clientes na União Europeia e nos Estados Unidos.
3. Avaliação de Controles de Segurança
3.1. Controles Implementados (Ativos Protegidos)
Rede e Sistemas: Firewall, Software Antivírus e rotinas de Backups.
Sistemas Legados: Monitoramento, manutenção e intervenção manual.
Segurança Física: Fechaduras (escritórios, loja, depósito), vigilância por CCTV e sistemas de detecção/prevenção de incêndio.
3.2. Controles Ausentes (Vulnerabilidades Identificadas)
Controle de Acesso: Falta de aplicação do Princípio do Menor Privilégio e Separação de Funções.
Gestão de Identidade: Ausência de sistema de gerenciamento centralizado e políticas fortes de senhas.
Segurança de Dados: Dados em repouso e em trânsito carecem de criptografia adequada.
Monitoramento e Resposta: Ausência de Sistema de Detecção de Intrusão (IDS).
Continuidade de Negócios: Inexistência de um Plano de Recuperação de Desastres (DRP).
4. Avaliação de Conformidade Regulatória
Devido às vulnerabilidades listadas, a empresa apresenta lacunas críticas em relação aos padrões do setor:
PCI DSS: NÃO CONFORME. Os dados de cartão de crédito não são armazenados de forma criptografada ou isolada.
GDPR: NÃO CONFORME. Dados de clientes europeus não estão seguros por criptografia e não há plano de notificação de violação (SLA de 72 horas).
SOC 1 e SOC 2: PARCIALMENTE CONFORME. A integridade dos dados é mantida, mas faltam políticas de controle de acesso de usuários e garantia de confidencialidade (PII/SPII).
5. Plano de Ação e Recomendações
Para mitigar riscos e evitar sanções, o departamento de TI deve priorizar:
Criptografia Imediata: Criptografar dados de pagamento e PII em repouso e em trânsito.
Gestão de Identidade (IAM): Adotar políticas de senhas fortes, autenticação multifator (MFA) e o modelo de Controle de Acesso Baseado em Funções (RBAC).
Monitoramento: Implantar um Sistema de Detecção de Intrusão (IDS) na rede.
Resiliência: Desenvolver e testar um Plano de Recuperação de Desastres (DRP) e um plano de Resposta a Incidentes (IR).
