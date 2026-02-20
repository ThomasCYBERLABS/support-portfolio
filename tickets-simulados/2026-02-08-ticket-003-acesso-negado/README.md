**Runbook usado:** [Grupo errado](/runbooks/grupo-errado.md)

- Sintoma: acesso negado ao abrir \\DC\Depto$\RH
- Usuário: teste.lab
- Diagnóstico: usuário em grupo incorreto
- Resolução: verificação AD + NTFS e usuário movido ao devido grupo
- Conclusão: o usuário estava no grupo "Financeiro" e não em seu grupo (RH), podendo ocasionar em acessos à arquivos não pertencentes e tornando inacessível à arquivos que realmente foram concedido as permissões para o usuário e grupo destinado.

# Evidências

**Sem acesso**
![RH](/tickets-simulados/2026-02-08-ticket-003-acesso-negado/evidencias/01-inauthorized-user-teste.labRH.png)

**Verificando AD/NTFS**
![Verify](/tickets-simulados/2026-02-08-ticket-003-acesso-negado/evidencias/02-verify-ad-ntfs-.png)



