# ot-comercial-homologacao
Ambiente exclusivo de homologação da OT Comercial V1.5 | OLEGARIO TECH. Testes de CRM, PWA e sincronização offline, sem dados reais.


## Homologação — atualização do upload de fotografias (05/11/2026)

A prévia é construída automaticamente a partir de `olegariotech-site/ot-comercial` na branch `feat/v1-5-integracao-premium-offline`. Esta publicação incorpora o upload POST-first e diagnóstico de erros, com cache PWA de homologação renovado para `v1-5-staging-v2`.

**Segurança:** sessão, IndexedDB e chave do cofre da prévia não foram alterados; pendências locais existentes devem permanecer acessíveis no mesmo navegador e perfil. Não apagar os dados de navegação. O projeto de produção não é atualizado por este workflow.

**Aceite pendente:** confirmar no Edge que a fotografia em `1 pendente` chega ao Supabase de testes; se falhar, anotar o erro que será exibido na faixa Campo offline.
