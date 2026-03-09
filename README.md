
# N2-MS900 – Desafio Oficial (Implementação)

Repositório de evidências e prints para o desafio MS-900 (Identidade, Licenças, Exchange Online e Teams).  
**Objetivo:** demonstrar a execução das tarefas via Microsoft 365 admin center / PowerShell (AzureAD/MS Graph).

## Estrutura do Repo
/
├─ docs/            # prints, evidências (opcional)
└─ README.md

---

## Módulo 1 – Identidade, Utilizadores e Grupos (Avançado)
**Funções:** User Administrator  
**Tarefas implementadas**
- Criar 8 utilizadores (naming padrão); 2 sem licença (estágio); 1 externo (B2B).
- Criar 5 grupos: GRP-TI, GRP-VENDAS, GRP-FINANCEIRO, GRP-DIRECAO, GRP-ESTAGIARIOS.
- Licenciamento via grupo para 3 grupos; grupo dinâmico (`department eq "Vendas"`).
- Bloquear login de 1 utilizador; forçar reset de password; renomear UPN; exportar lista (CSV).

---

## Módulo 2 – Licenças, Subscrições e Custos
**Funções:** User Administrator, Billing Reader  
**Tarefas implementadas**
- Inventário de licenças (disponíveis vs atribuídas); atribuição **apenas via grupo**; remoção de atribuição direta.
- Comparativo M365 Business vs E3 (print); utilizadores sem licença; simulação de +20 utilizadores; serviços desativados na SKU; relatório de consumo.
- Política de compra de licenças; validação automática ao entrar no grupo.



---

## Módulo 3 – Exchange Online (Gestão Operacional)
**Funções:** Exchange Administrator  
**Tarefas implementadas**
- Criar 2 shared mailboxes (financeiro@, suporte@) e atribuir permissões.
- Converter mailbox de utilizador em shared; criar Mail Contact externo; auto-reply interno/externo; regra de encaminhamento; desativar POP/IMAP.
- Criar Mail-enabled Security Group; verificar limites de envio; consultar **Message trace**.


---

## Módulo 4 – Microsoft Teams (Colaboração Avançada)
**Funções:** Teams Administrator  
**Tarefas implementadas**
- Criar 3 equipas (Vendas, TI, Financeiro); canais privados e partilhados; membros via grupo M365; proprietários distintos.
- Políticas de mensagens; bloquear criação de equipas por utilizadores; agendar reunião com gravação; chat de grupo; retenção.


---
