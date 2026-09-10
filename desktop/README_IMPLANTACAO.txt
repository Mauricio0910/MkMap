MarketMap - Módulo Checkpoints + Relatórios 360

Arquivos principais:
- index.html: sistema atualizado.
- sw.js: cache PWA atualizado para evitar versão antiga.
- manifest.json: configuração PWA/mobile.
- icon-192.png e icon-512.png: ícones do PWA.
- FIRESTORE_REGRAS_CHECKPOINTS.txt: exemplo de regra caso sua base bloqueie a nova coleção checkpoints.

O que foi adicionado:
1. Aba 📍 Checkpoints.
   - Captura GPS no local atual do consultor.
   - Usa Google Geocoder para tentar identificar rua, bairro, cidade e estado.
   - Permite vincular o checkpoint a uma empresa já cadastrada.
   - Permite criar/atualizar a empresa na coleção companies.
   - Salva histórico na nova coleção checkpoints.

2. Aba 📈 Relatórios 360.
   - Une informações de companies + checkpoints.
   - Filtros por Rua, Bairro, Cidade, Estado e Segmento.
   - Filtros por status e busca livre.
   - KPIs de clientes, checkpoints, oportunidades, clientes potenciais, clientes de concorrentes e sem sistema.
   - Exportação CSV.

Publicação:
- Substitua os arquivos atuais no GitHub por estes arquivos.
- Depois publique novamente no Vercel/Netlify/GitHub Pages/Firebase Hosting.
- Após publicar, faça Ctrl+F5 no desktop e limpe cache/abra guia anônima no celular.

Atenção:
- O checkpoint depende de HTTPS para o navegador permitir geolocalização.
- Se a coleção checkpoints não salvar, ajuste as regras do Firestore usando o arquivo FIRESTORE_REGRAS_CHECKPOINTS.txt.
- O código mantém a coleção companies atual, sem rotina de apagar registros existentes.
