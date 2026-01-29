# Decisiones de Workflow - Mi Proyecto
## ¿Cuándo usamos rebase?
- Para limpiar commits locales antes de hacer push
- Para mantener un historial lineal en ramas de feature
- Ejemplo: Usamos `git rebase -i` para combinar 5 commits
 de correcciones en uno solo antes del PR
## ¿Cuándo usamos merge?
- Para integrar ramas de feature a main
- Cuando queremos preservar el contexto de cuándo se unió
- Ejemplo: Merge de feature/login a main con merge commit
## ¿Cuándo usamos cherry-pick?
- Para aplicar hotfixes urgentes sin traer código incompleto
- Ejemplo: Cherry-pick del fix de validación a main
## Lecciones aprendidas
- El rebase es poderoso pero peligroso en ramas compartidas
- Siempre verificar con reflog antes de entrar en pánico
