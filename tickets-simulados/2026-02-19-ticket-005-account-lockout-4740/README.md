**Runbook usado:** [Conta bloqueada](/runbooks/conta-bloqueada-4740.md)

- Sintoma: usuário não consegue logar / conta bloqueada
- Usuário: teste.lab
- Diagnóstico: confirmado por Event ID 4740 no DC
- Origem: Caller Computer Name = DESKTOP-LUH6IIF
- Resolução: unlock + orientação para remover as credenciais antigas (simulado)
- Validação: login ok

# Evidências

**Conta bloqueada**
![Bloqueio ao logar](/tickets-simulados/2026-02-19-ticket-005-account-lockout-4740/evidencias/01-blockaccount.png)

**Filtrando evento no DC**
![4740](/tickets-simulados/2026-02-19-ticket-005-account-lockout-4740/evidencias/02-event4740.png)

**Confirmação**
![Check](/tickets-simulados/2026-02-19-ticket-005-account-lockout-4740/evidencias/03-confirmacao.png)

**Desbloquando conta**
![Unlock](/tickets-simulados/2026-02-19-ticket-005-account-lockout-4740/evidencias/04-unlock.png)

**Conclusão**
![Final](/tickets-simulados/2026-02-19-ticket-005-account-lockout-4740/evidencias/05-final.png)