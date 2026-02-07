**Runbook usado:** [Triagem - Sem Internet](/runbooks/network/triagem-sem-internet.md)

- Sintoma: Usuário sem internet (navegação indisponível)
- Nome do usuário: teste.lab
- Impacto: Não acessa sistemas/web
- Prioridade: P2
- Descrição: Usuário relata que internet caiu
- Tentativas do usuário: Reiniciou navegador
- Diagnóstico: DNS configurado manualmente com servidores inválidos
- Resolução: Ajustado DNS para automático (DHCP) ou DNS válido, flushdns, testes ok 
- Validação: Ping IP ok, nslookup ok, navegação ok
- Causa provável (simulada): Alteração indevida, VPN, configuração manual anterior
- Prevenção: Padronizar DNS via GPO/DHCP