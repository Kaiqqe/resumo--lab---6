Resumo do Lab: Governança e Conformidade no Azure

Durante o laboratório “Governança e Conformidade”, aprofundei minhas noções sobre como garantir que os recursos em nuvem sigam regras, políticas e boas práticas, assegurando segurança, padronização e controle.

🎯 Principais conceitos aprendidos
1. Governança em ambientes de nuvem

Governança significa estabelecer regras, processos e estrutura para administrar quem pode fazer o quê dentro da nuvem.

Envolve definir políticas, roles (funções) e responsabilidades para evitar desperdício, uso indevido ou configurações inseguras.

2. Controle de acesso e identidade

Uso do Azure Active Directory (Azure AD) para gerenciar identidades e autenticação centralizada.

Aplicação do conceito de princípio do menor privilégio: conceder apenas permissões mínimas necessárias para executar tarefas.

Funções pré-definidas e personalizadas (RBAC – Role-Based Access Control) para controlar quem pode fazer operações nos recursos.

3. Políticas e compliance

Azure Policy: serviço que permite criar, atribuir e gerenciar políticas que impõem regras e efeitos para os recursos. Ex: “todas as VMs devem usar discos gerenciados”, “nenhum recurso fora de uma região específica”.

Iniciativas de políticas: agrupamentos de políticas que facilitam aplicar conjuntos de regras com coerência.

Compliance implica garantir que os ambientes cumpram padrões (legais, regulatórios ou internos), como leis de proteção de dados ou normas da empresa.

4. Blueprints do Azure

Azure Blueprints: modelo de implantação que agrupa artefatos como políticas, roles e templates ARM para padronizar ambientes.

Permite provisionar ambientes conforme as diretrizes de governança, garantindo consistência e conformidade desde o início.

5. Monitoramento e auditoria

Logs de atividade (Activity Logs): registro de operações feitas nos recursos (quem fez, o quê, quando).

Azure Monitor / Azure Security Center: ferramentas para detectar anomalias e aplicar alertas de segurança.

Policy compliance dashboard: painel para ver quais recursos violam políticas definidas, para correção contínua.

🧠 Integração com o que já vi

Quando estudei estrutura de recursos, grupos e organização, agora entendo que essa estrutura também suporta governança (quem pode criar, modificar, excluir).

As práticas de segurança e boas práticas de arquitetura se conectam diretamente com governança, porque não basta projetar bem — é necessário fazer cumprir.

No módulo de custos, vimos que políticas e tags ajudam a alocar e controlar gastos — aqui percebemos que essas regras não são só recomendadas, mas podem ser impostas via governança.

✅ Conclusão do Lab

Esse módulo sobre Governança e Conformidade foi essencial para perceber que em nuvem, autonomia sem controle pode gerar caos. Saber definir permissões, políticas, realizar auditoria e implantar ambientes padronizados garante:

segurança e redução de risco humano;

compliance com normas internas/externas;

ambientes consistentes e organizados.

Agora me sinto mais preparado para construir arquiteturas no Azure que não só funcionam, mas também obedecem às regras e boas práticas de governança.
