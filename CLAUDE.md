# site-cnh — Projeto Honda

Pré-contrato de consórcio CNH, aberto em `/:slug/cnh`.

- Arquivo principal do site: `index.html` (HTML+CSS+JS em um único arquivo, sem build). Deploy automático pela Vercel a partir da `main` (inferido).
- Banco: Supabase (projeto `vendashonda`), usado direto pelo navegador com a chave pública (anon). Nunca colocar `service_role`, tokens ou senhas aqui: este repositório é público.
- Contexto completo, regras e histórico: https://github.com/FilipeCapelasso/atualiza-o-projeto-Honda (leia o README, o PROJECT_CONTEXT e o topo do docs/CHANGELOG antes de editar).
- Depois de alterar o site: registre a mudança no docs/CHANGELOG do hub. O espelho em `apps/` do hub é atualizado automaticamente por GitHub Action; não edite lá.
- Ao editar: faça a menor mudança segura, preserve os demais vendedores e confira o último commit antes (outra conta pode ter mexido).
