**Runbook usado:** [GPO - Não Aplica](/runbooks/GPO/gpo-nao-aplica.md)

- Sintoma: drive Z não aparece
- Diagnóstico: GPO não aplicada por security filtering
- Resolução: corrigido security filtering / grupo correto
- Validação: gpresult mostra GPO aplicada + drive mapeado

# Evidências

**Sem drive Z**
![Drive](evidencias/no-have-drive-Z.png)

**gpresult /r**
![gpresult](evidencias/gpresult.png)

**Drive volta**
![Drive-back](evidencias/drive-back.png)

**gpresult /r(2)**
![gpresult /r](evidencias/gpresult2.png)

**Event viewer**
![GPO-logs](evidencias/eventviewer.png)