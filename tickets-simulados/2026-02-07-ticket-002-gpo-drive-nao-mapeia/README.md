**Runbook usado:** [GPO - Não Aplica](/runbooks/GPO/gpo-nao-aplica.md)

- Sintoma: drive Z não aparece
- Diagnóstico: GPO não aplicada por security filtering
- Resolução: corrigido security filtering / grupo correto
- Validação: gpresult mostra GPO aplicada + drive mapeado

# Evidências

**Sem drive Z**
![Drive](evidencias/1-no-have-drive-Z.png)

**gpresult /r**
![gpresult](evidencias/2-gpresult.png)

**Drive volta**
![Drive-back](evidencias/3-drive-back.png)

**gpresult /r(2)**
![gpresult /r](evidencias/4-gpresult2.png)

**Event viewer**
![GPO-logs](evidencias/5-eventviewer.png)