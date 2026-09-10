MarketMap Mobile — Checkpoints de Campo

Versão otimizada para smartphones.

Principais recursos adicionados:
- Botão flutuante Checkpoint agora, visível no celular.
- Captura de GPS com preenchimento de rua, bairro, cidade e estado.
- Campos de localização editáveis para corrigir endereço quando o GPS/Google não identificar bem.
- Formulário de checkpoint em uma coluna para facilitar uso no celular.
- Lista de segmentos sugeridos para acelerar o cadastro.
- Botão de salvar checkpoint fixo durante o preenchimento mobile.
- Relatório 360 com visualização em cards no celular e tabela no desktop.

Publicação:
1. Substitua index.html, sw.js e manifest.json no repositório.
2. Publique no GitHub/Vercel/Netlify/Firebase Hosting.
3. No celular, limpe o cache ou abra em guia anônima no primeiro teste.
4. O GPS só funciona corretamente em HTTPS.

Firestore:
Além da coleção companies, esta versão usa a coleção checkpoints.
Se suas regras restringirem coleções, libere leitura/gravação para usuários autenticados na coleção checkpoints.
