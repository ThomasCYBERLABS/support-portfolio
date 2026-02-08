**Runbook usado:** [Erro de criação](/runbooks/Permissões/erro-criação-arquivo.md)

- Sintoma: bloqueada a criação de pasta/arquivo
- Usuário: teste.lab
- Pasta\caminho: \\DC0\Depto$\Financeiro
- Diagnóstico: Share impedindo (Read only), NTFS ok
- Resolução: ajustar/expandir permissões Share

# Evidências

**Criação não autorizada**
![Erro ao criar pasta/arquivo](/tickets-simulados/2026-02-08-ticket-004-erro-de-criação/evidencias/01-failed-creation-user-test.labfinanceiro.png)

**Permissões Share**
![Read only](/tickets-simulados/2026-02-08-ticket-004-erro-de-criação/evidencias/02-share-readonly.png)